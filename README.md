# 🏥 MCP Health - Pipeline Health Monitoring Dashboard

Interactive demos for data pipeline health monitoring, Slack integration, and automated management.

## 🚀 Live Demos

- **[Hub Page](https://alonhaze7.github.io/MCP-Health/)** - Main navigation hub
- **[Slack Insights](https://alonhaze7.github.io/MCP-Health/slack-insights.html)** - Interactive Slack bot demo with real-time alerts
- **[Health Dashboard](https://alonhaze7.github.io/MCP-Health/health-dashboard.html)** - Comprehensive monitoring dashboard
- **[Headless Actions](https://alonhaze7.github.io/MCP-Health/headless-actions.html)** - Automated pipeline management reference

## 📋 What's Included

### 1. 💬 Slack Insights & Actions
An interactive Slack interface demonstration showing:
- **Morning Health Summary** - Daily 8am report with health score, status counts, and top issues
- **Critical Alerts** - Real-time failure notifications with context and AI suggestions
- **Auto-Repair Actions** - One-click remediation for common issues
- **Conversational AI** - Natural language queries about pipeline status
- **7-Day History** - Visual sparklines showing pipeline trends
- **Token Expiry Warnings** - Proactive alerts before authentication failures

**Key Features:**
- Interactive message cards with action buttons
- Real-time status badges (🟢 healthy, 🟡 warning, 🔴 failed)
- AI-powered suggestions for each failure type
- Modal confirmations for repair actions
- Sidebar dashboard with expandable sections

### 2. 📊 Health Dashboard
A comprehensive monitoring dashboard featuring:
- **Campaign Performance Summary** - High-level metrics and AI-generated insights
- **Key Metrics Cards** - Spend, Revenue, ROAS, ROI with trend charts
- **Channel Distribution** - Donut chart showing revenue by channel
- **Pipeline Status Table** - Real-time view of all 17 pipelines with:
  - Status badges and health indicators
  - Record counts and success rates
  - 7-day trend sparklines
  - Last run timestamps
  - Click-through for detailed views

**Design Highlights:**
- Matches the reference design screenshot provided
- Responsive grid layout
- Chart.js powered visualizations
- Progress bars and animated metrics
- Color-coded status system

### 3. ⚙️ Headless Actions
A comprehensive reference guide for automated actions:

#### Health Monitoring
- **Pipeline Health Check** - 5-minute interval monitoring
- **Data Quality Validator** - Real-time schema and anomaly detection
- **Token Expiry Monitor** - Proactive OAuth token tracking

#### Auto-Repair
- **Adaptive Rate Limiter** - Exponential backoff for API throttling
- **Auto Token Refresh** - Automatic OAuth renewal before expiration
- **Smart Retry Handler** - Circuit breaker pattern for transient failures

#### Data Management
- **Auto Backfill Scheduler** - Gap detection and recovery
- **Data Deduplicator** - Hourly duplicate removal
- **Stale Data Archiver** - Automatic cold storage migration

#### Notifications
- **Daily Health Summary** - 8am Slack reports
- **Critical Alert Dispatcher** - Real-time failure notifications
- **Weekly Performance Report** - Trends and optimization tips

**Technical Details:**
- API integration examples
- Code snippets for triggering actions
- Status monitoring endpoints
- Configurable trigger conditions

## 🛠️ Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with gradients and animations
- **JavaScript (ES6+)** - Interactive features and real-time updates
- **Chart.js** - Data visualization library
- **No frameworks** - Pure vanilla JS for maximum compatibility

## 🎨 Design System

### Colors
- Primary: `#667eea` → `#764ba2` (gradient)
- Success: `#48bb78` (green)
- Warning: `#ed8936` (orange)
- Critical: `#f56565` (red)
- Background: `#f5f7fa` (light) / `#0f172a` (dark)

### Typography
- System font stack: `-apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto'`
- Slack font: `'Slack-Lato'` for Slack demo

### Components
- Rounded corners: `8px - 16px`
- Shadows: `0 1px 3px rgba(0,0,0,0.1)`
- Transitions: `0.2s - 0.3s ease`
- Responsive breakpoints: `768px, 1200px`

## 📱 Responsive Design

All pages are fully responsive with:
- Mobile-first approach
- Flexible grid layouts
- Adaptive navigation
- Touch-friendly interactive elements
- Optimized for screens from 320px to 2560px

## 🔧 Local Development

1. Clone the repository:
```bash
git clone https://github.com/alonhaze7/MCP-Health.git
cd MCP-Health
```

2. Open in browser:
```bash
open index.html
# or use a local server
python -m http.server 8000
# then visit http://localhost:8000
```

## 📦 File Structure

```
MCP-Health/
├── index.html              # Main hub page
├── slack-insights.html     # Slack integration demo
├── health-dashboard.html   # Monitoring dashboard
├── headless-actions.html   # Automation reference
└── README.md              # This file
```

## 🌟 Use Cases

### For Demos
- Client presentations showing pipeline monitoring capabilities
- Internal stakeholder reviews
- Product feature showcases
- Training and onboarding materials

### For Development
- Reference implementation for Slack bot design
- Dashboard UI/UX patterns
- Automation documentation
- API integration examples

### For Documentation
- Visual guide to pipeline health concepts
- Automation action catalog
- Best practices for monitoring
- Alert and notification patterns

## 🚦 Getting Started

1. **Navigate to the Hub** - Start at `index.html` to explore all three demos
2. **Slack Insights** - See how alerts and notifications work in Slack
3. **Health Dashboard** - Explore real-time monitoring and metrics
4. **Headless Actions** - Learn about automation capabilities

## 🤝 Contributing

This is a demo repository. Feel free to fork and customize for your needs!

## 📄 License

MIT License - feel free to use and modify as needed.

## 📧 Contact

For questions or feedback, please open an issue in the GitHub repository.

---

**Built with ❤️ for Data Pipeline Health Management**
