graph TD
%% 主节点层
    A[OMap-GeoDB_gpkg]
    D[oData-railway_series]
    H[oData-power_series]
    M[oData-aeroways]
    P[oData-water&damn]
    V[oDa]

%% 文件名约束分支
    A --> B[文件名约束]
    B -->|禁止字符| C[/\:*?"<>|]
    
%% Railway系列
    D --> E[.gpkg]
    D --> F[railway_line]
    D --> G[railway-station-point]
    D --> oData((oData格式))

%% Power系列
    H --> I[.gpkg]
    H --> J[power_point]
    H --> K[power_line]
    H --> L[power_polygon]
    H --> oData
    
%% 航空路线
    M --> N[.gpkg]
    M --> O[aeroways_line]
    M --> oData

%% 水利设施
    P --> Q[.gpkg]
    P --> R["water line"]
    P --> S[$$water\_polygon$$]
    P --> T[damn_line]
    P --> U[damn_polygon]
    P --> oData

%% 未完成节点
    V --> W[...]
    
%% 格式统一说明
    style oData fill:#f9f,stroke:#333
    classDef red fill:#f96;
    class C,B red;
