# 地理数据库结构图

```mermaid
graph TD
%%=============== 主节点定义 ===============%%
    A[OMap-GeoDB_gpkg]
    D[oData-railway_series]
    H[oData-power_series]
    M[oData-aeroways]
    P[oData-water&damn]
    V[oDa]

%%=============== 文件约束规则 ===============%%
    A --> B[文件名约束]
    B -->|禁止字符| C[/\:*?"<>|]
    class B,C constraintStyle

%%=============== Railway系列 ===============%%
    D --> E[.gpkg]
    D --> F[railway_line]
    D --> G[railway-station-point]
    D --> oData((oData格式))
    class E fileFormat

%%=============== Power系列 ===============%%
    H --> I[.gpkg]
    H --> J[power_point]
    H --> K[power_line]
    H --> L[power_polygon]
    H --> oData
    class I fileFormat

%%=============== 航空路线 ===============%%
    M --> N[.gpkg]
    M --> O[aeroways_line]
    M --> oData
    class N fileFormat

%%=============== 水利设施 ===============%%
    P --> Q[.gpkg]
    P --> R["water line"]
    P --> S[water_polygon]
    P --> T[damn_line]
    P --> U[damn_polygon]
    P --> oData
    class Q fileFormat

%%=============== 未完成节点 ===============%%
    V --> W[...]
    class V incomplete

%%=============== 样式定义 ===============%%
    classDef fileFormat fill:#87CEEB,stroke:#2B6A94;
    classDef constraintStyle fill:#FF6347,stroke:#8B0000;
    classDef incomplete fill:#D3D3D3,stroke:#696969;
    style oData fill:#DA70D6,stroke:#4B0082,stroke-width:2px;
