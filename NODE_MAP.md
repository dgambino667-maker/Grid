# ABCANNA 3D Network Node Map

## Network Overview
**Title:** ABCANNA Distributors: CRM-Inventory-Grok AI Integration Network

This is a 3D force-directed graph visualization showing the interconnected systems in the ABCANNA distribution network.

---

## Nodes by Group

### Group 1: Central Hub (Orange - #FFAA00)
| Node | Description | Size |
|------|-------------|------|
| **Bud Center CRM** | Central Sales, Orders & Production Hub | 25 |

### Group 2: Inventory & Compliance (Cyan - #00CCFF)
| Node | Description | Size |
|------|-------------|------|
| **Canix** | Finished Goods, Splits, Orders & Invoicing | 18 |
| **Metrc** | State Compliance, Traceability & Manifests | 18 |

### Group 3: Forecasting (Green - #88FF88)
| Node | Description | Size |
|------|-------------|------|
| **Internal Excel** | Par Levels, Reorder, Safety Stock | 16 |

### Group 4: Automation (Magenta - #FF88FF)
| Node | Description | Size |
|------|-------------|------|
| **Python Scripts** | ETL, Automation & File Drops | 15 |

### Group 5: AI Intelligence (Hot Pink - #FF0088)
| Node | Description | Size |
|------|-------------|------|
| **Grok API** | AI Analysis, KPIs, Forecasting & Alerts | 22 |

### Group 6: Dashboards & Notifications (Cyan-Green - #00FFAA)
| Node | Description | Size |
|------|-------------|------|
| **KPIs Dashboards** | Live Dashboards & Visualizations | 17 |
| **80" TV Dashboard** | Warehouse Live Display | 14 |
| **Team Notifications** | Email / Slack / Superbud Alerts | 12 |

### Group 7: Future Expansion (Light Purple - #AA88FF)
| Node | Description | Size |
|------|-------------|------|
| **SaaS Overlay** | Pluggable Compliance & Predictive Layer | 13 |

### Group 8: Data Input (Gold - #FFCC00)
| Node | Description | Size |
|------|-------------|------|
| **Production Inputs** | ProSeal / QR Scanners / Team | 14 |

---

## Data Flow & Connections

### Entry Points
```
Production Inputs (ProSeal/QR Scanners/Team)
    ↓
Bud Center CRM (Central Hub)
```

### Primary Flows

#### 1. **Bud Center CRM → Downstream Systems**
- → **Canix** (Orders & Invoicing) - Strength: 8
- → **Metrc** (Compliance) - Strength: 8
- → **Internal Excel** (Forecasting) - Strength: 6
- → **Python Scripts** (ETL) - Strength: 10

#### 2. **Data Aggregation → Python Scripts**
- **Canix** → Python Scripts - Strength: 5
- **Metrc** → Python Scripts - Strength: 5
- **Internal Excel** → Python Scripts - Strength: 6
- **Python Scripts** → **Grok API** - Strength: 12

#### 3. **Grok API Outputs**
- → **KPIs Dashboards** - Strength: 10
- → **80" TV Dashboard** - Strength: 8
- → **Team Notifications** - Strength: 7
- → **SaaS Overlay** - Strength: 6
- → **Bud Center CRM** (Feedback loop) - Strength: 4

#### 4. **Dashboard Interconnection**
- **KPIs Dashboards** → **80" TV Dashboard** - Strength: 5

---

## Connection Strength Legend
- **12**: Python Scripts ↔ Grok API (Strongest - Core AI Processing)
- **10**: Bud Center CRM ↔ Python Scripts (Primary Data Export)
- **10**: Grok API → KPIs Dashboards (Major Output)
- **8**: Bud Center CRM ↔ Canix (High Volume)
- **8**: Bud Center CRM ↔ Metrc (High Volume)
- **8**: Grok API → 80" TV (Live Display Feed)
- **7**: Production Inputs → Bud Center CRM (Field Data)
- **7**: Grok API → Team Notifications (Alert System)
- **6**: Bud Center CRM → Internal Excel (Forecast Input)
- **6**: Internal Excel → Python Scripts (Optimization Data)
- **6**: Grok API → SaaS Overlay (Future Integration)
- **5**: Canix ↔ Python Scripts (Order Data)
- **5**: Metrc ↔ Python Scripts (Compliance Data)
- **5**: KPIs Dashboards → 80" TV (Dashboard Sync)
- **4**: Grok API → Bud Center CRM (Feedback/Alerts)

---

## System Architecture Layers

### Layer 1: Data Sources
- **Production Inputs** (Field data from operations)
- **Bud Center CRM** (Central operational hub)

### Layer 2: Data Systems
- **Canix** (Inventory management)
- **Metrc** (Compliance tracking)
- **Internal Excel** (Forecasting models)

### Layer 3: Processing & Intelligence
- **Python Scripts** (ETL & automation)
- **Grok API** (AI-powered analysis & predictions)

### Layer 4: Output & Visualization
- **KPIs Dashboards** (Live metrics)
- **80" TV Dashboard** (Warehouse visibility)
- **Team Notifications** (Alerts & communications)

### Layer 5: Future State
- **SaaS Overlay** (Expandable compliance & predictive layer)

---

## Key Insights

### Central Hub Role
**Bud Center CRM** is the network hub with connections to 4 major systems, making it critical for operations.

### AI Processing Bottleneck
**Grok API** processes data from Python Scripts and distributes to 4 output systems, making it a critical intelligence layer.

### Data Pipeline
```
Production Data → CRM → Python Scripts → Grok AI → Dashboards → Team
                  ↓        ↓              ↓
              Canix     Metrc        SaaS Overlay
              Excel
```

### Feedback Mechanism
Grok API feeds results back to Bud Center CRM, enabling continuous optimization.

---

## Visual Characteristics

- **Node Colors**: Represent different functional groups
- **Node Size**: Indicates system complexity/importance (larger = more central)
- **Link Colors**: Match source node color for easy tracing
- **Link Width**: Fixed at 2px (can be adjusted for flow magnitude)
- **Arrows**: Directional flow indicators with curvature (0.2)
- **3D Physics**: Force-directed layout for organic spacing

---

## Interactive Features

Click any node in the 3D visualization to see:
- Node name
- Full description
- Functional role in the network

---

## File Structure
- **Nodes**: 11 total
- **Links**: 15 total
- **Groups**: 8 functional categories
- **Color Palette**: 8 distinct colors for visual separation

---

## How to Use

1. Save the HTML visualization code to a file (e.g., `index.html`)
2. Open it in a web browser to interact with the 3D network
3. Use mouse to rotate, zoom, and pan the graph
4. Click nodes to see detailed information
5. Reference this node map document to understand system relationships
