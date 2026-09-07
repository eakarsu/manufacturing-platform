# Feature status — Manufacturing, quality & maintenance

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 400 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | Native records/view |
| Tasks | records | 1 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 14 | 0 | Native records/view |
| Activity & audit trail | audit | 10 | 0 | Native records/view |
| Provider connections | integration | 4 | 0 | Provider request records only |
| Supplier contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material grade registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Index source control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Publication date validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Formula price calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lag period validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Floor ceiling control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Freight differential audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy surcharge validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Currency conversion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Off-spec quality credits | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume rebate calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice matching | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Supplier exception workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material supplier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Manufacturing agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| BOM and routing versioning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material receipt ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Production-order reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material usage variance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Yield and scrap calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scrap ownership and resale credit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rework responsibility analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Labor and conversion-cost validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overtime and premium audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material substitution control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality rejection chargeback | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Finished-goods reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier recovery package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Debit and credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site product and supplier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product, Serial & Lot Genealogy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Warranty Policy & Entitlement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer Warranty Claim Intake | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dealer & Service-Center Validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Failure-Code Normalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Failed-Component Evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Root-Cause & Failure Clustering | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier Responsibility Determination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Warranty Cost Reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier Claim Package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier Response & Negotiation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Debit Memo & Chargeback Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Warranty Recovery Ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Warranty Reserve Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier Performance Scorecards | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recall & Field-Action Early Warning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| VMI contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Storeroom bin registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Item substitute master | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Beginning inventory reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Receipt issue ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cycle count variance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Consumption billing calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Price discount validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Obsolete inventory responsibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency premium audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Restocking fee control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier discrepancy workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plant item analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tooling agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset serial registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ownership title evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Purchase order reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Amortization schedule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Piece-price amortization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume threshold monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate tooling detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance responsibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refurbishment validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier custody tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| End-of-program transfer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Residual balance recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tool return workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program supplier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Powder Reuse Plan | records | 1 | 0 | Native records/view |
| Print Parameter Tuning | records | 1 | 0 | Native records/view |
| Failure Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material Selection Advisor | records | 1 | 0 | Native records/view |
| Build Time Estimation | records | 1 | 0 | Native records/view |
| Quality Scoring | records | 1 | 0 | Native records/view |
| Print Jobs Management | records | 1 | 0 | Native records/view |
| Material Inventory | records | 1 | 0 | Native records/view |
| Printer Management | records | 1 | 0 | Native records/view |
| Print Profiles | records | 1 | 0 | Native records/view |
| Maintenance Logs | records | 2 | 0 | Native records/view |
| Printing tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assembly line visual inspector work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| BOM Items | records | 1 | 0 | Native records/view |
| Alternative Parts | records | 1 | 0 | Native records/view |
| Obsolescence | records | 1 | 0 | Native records/view |
| Lead Time | records | 1 | 0 | Native records/view |
| Cost-Down | records | 1 | 0 | Native records/view |
| Suppliers | records | 1 | 0 | Native records/view |
| Inventory | records | 1 | 0 | Native records/view |
| Compliance | records | 2 | 0 | Native records/view |
| BOM Versions | records | 1 | 0 | Native records/view |
| Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Webhooks | integration | 2 | 0 | Provider request records only |
| Supplier pcn impact matrix | records | 1 | 0 | Native records/view |
| Robot Programs | records | 1 | 0 | Native records/view |
| Task Sequences | records | 1 | 0 | Native records/view |
| Safety Boundaries | records | 1 | 0 | Native records/view |
| Quality Checkpoints | records | 1 | 0 | Native records/view |
| Demonstration Recordings | records | 1 | 0 | Native records/view |
| Waypoints | records | 1 | 0 | Native records/view |
| Tool Configurations | records | 1 | 0 | Native records/view |
| Work Cells | records | 1 | 0 | Native records/view |
| AI Motion Planning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Quality Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Safety Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Task Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fixture Changeover Coach | records | 1 | 0 | Native records/view |
| AI Anomaly Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Natural Language Programming | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Predictive Maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Motion Path Replay | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Task Optimisation Batch | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Safety Boundary Auto-Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive Maintenance Scheduler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cross-Model Motion Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality Checkpoint Auto-Designer | integration | 1 | 0 | Provider request records only |
| NL Program Debugger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agentic Program Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Failure Root-Cause Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cycle-Time Estimator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operator Training Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Digital Twins | records | 1 | 0 | Native records/view |
| Personalities | records | 1 | 0 | Native records/view |
| Conversations | records | 1 | 0 | Native records/view |
| Knowledge Base | records | 1 | 0 | Native records/view |
| Behavior Patterns | records | 1 | 0 | Native records/view |
| Sentiment Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Memory System | records | 1 | 0 | Native records/view |
| Response Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training Data | records | 1 | 0 | Native records/view |
| Interaction History | records | 1 | 0 | Native records/view |
| Twin Comparison | records | 1 | 0 | Native records/view |
| Text Summarizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CF: ContinuousTwinLearning | records | 1 | 0 | Native records/view |
| CF: MultiTwinSocialDynamics | records | 1 | 0 | Native records/view |
| CF: EmotionalStateEvolution | records | 1 | 0 | Native records/view |
| CF: LongTermRelationshipMode | records | 1 | 0 | Native records/view |
| CF: CounterfactualAnalysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gap: MissingGenerateConversat | records | 1 | 0 | Native records/view |
| Gap: NoConversationalAiBacken | records | 1 | 0 | Native records/view |
| Gap: LimitedLlmProviderIntegr | integration | 1 | 0 | Provider request records only |
| Gap: NoRealTimeInteractionInt | records | 1 | 0 | Native records/view |
| Gap: NoMultiUserGroupConversa | records | 1 | 0 | Native records/view |
| Gap: NoPaymentBillingModule | records | 1 | 0 | Native records/view |
| Gap: NoReportingBeyondStubs | records | 1 | 0 | Native records/view |
| Twin drift monitor | records | 1 | 0 | Native records/view |
| Devices | records | 1 | 0 | Native records/view |
| Telemetry | records | 2 | 0 | Native records/view |
| Alerts | records | 3 | 0 | Native records/view |
| Firmware | records | 1 | 0 | Native records/view |
| Edge inference | records | 1 | 0 | Native records/view |
| Smart agents | records | 1 | 0 | Native records/view |
| Fleet ops ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic device health monitor predicting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| federated learning for edge models train | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| smart agent orchestration coordinating c | records | 1 | 0 | Native records/view |
| device marketplace integration auto disc | integration | 1 | 0 | Provider request records only |
| energy efficiency optimizer extending ex | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| av anomaly detection for camera and | records | 1 | 0 | Native records/view |
| automated rule tuning from historical | records | 1 | 0 | Native records/view |
| predictive bandwidthcost optimizer fo | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| videoaudio anomaly detection for av | records | 1 | 0 | Native records/view |
| mqtt broker integration only http | integration | 1 | 0 | Provider request records only |
| ota firmware delivery pipeline only | records | 1 | 0 | Native records/view |
| multi tenant fleet partitioning | records | 1 | 0 | Native records/view |
| audit log 0 references | records | 1 | 0 | Native records/view |
| notification engine 0 references | records | 1 | 0 | Native records/view |
| webhook dispatch for alerts to | integration | 1 | 0 | Provider request records only |
| Firmware rollback window | records | 1 | 0 | Native records/view |
| Sensor Management | records | 2 | 0 | Native records/view |
| Equipment Registry | records | 3 | 0 | Native records/view |
| Maintenance Scheduling | records | 1 | 0 | Native records/view |
| Anomaly Detection | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Predictive Maintenance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Root Cause Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sensor calibration drift | records | 1 | 0 | Native records/view |
| agentic maintenance coordinator predicti | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| federated anomaly detection trained on a | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| vibration acoustic monitoring for early | records | 1 | 0 | Native records/view |
| supply chain disruption prediction corre | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| energy efficiency optimizer recommending | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| cross equipment correlation extending co | records | 1 | 0 | Native records/view |
| detect anomaly endpoint with ml | records | 1 | 0 | Native records/view |
| predict failure endpoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| root cause ai synthesis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| energy optimization ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| equipment health score ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| maintenance recommendation ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| mqtt broker only http ingestion | records | 1 | 0 | Native records/view |
| real plcscada integration only integr | integration | 1 | 0 | Provider request records only |
| technician dispatch mobile workflow | records | 1 | 0 | Native records/view |
| sla tracking | records | 1 | 0 | Native records/view |
| webhook surface | integration | 1 | 0 | Provider request records only |
| notifications module 0 references | records | 1 | 0 | Native records/view |
| websocket real time telemetry stream | records | 1 | 0 | Native records/view |
| Shift Management | records | 2 | 0 | Native records/view |
| Charts & Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Routes | records | 1 | 0 | Native records/view |
| Safety | records | 1 | 0 | Native records/view |
| Assembly | records | 1 | 0 | Native records/view |
| Supply chain | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scrap rework loop | records | 1 | 0 | Native records/view |
| Admin | records | 1 | 0 | Native records/view |
| File upload | records | 1 | 0 | Native records/view |
| Data export | records | 1 | 0 | Native records/view |
| Gl chart of accounts | records | 1 | 0 | Native records/view |
| Ap ar | records | 1 | 0 | Native records/view |
| Inventory gl | records | 1 | 0 | Native records/view |
| Mrp | records | 1 | 0 | Native records/view |
| Boms | records | 1 | 0 | Native records/view |
| Cost accounting | records | 1 | 0 | Native records/view |
| Consolidations | records | 1 | 0 | Native records/view |
| Multi currency | records | 1 | 0 | Native records/view |
| Intercompany | records | 1 | 0 | Native records/view |
| Feedback | records | 1 | 0 | Native records/view |
| Api docs | records | 1 | 0 | Native records/view |
| Privacy policy | records | 1 | 0 | Native records/view |
| Terms of service | records | 1 | 0 | Native records/view |
| General Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Process Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive Modeling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Troubleshooting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Literature Search | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Protocol Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data Interpreter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scale-Up Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Processes | records | 1 | 0 | Native records/view |
| Strains | records | 1 | 0 | Native records/view |
| Recipes | records | 1 | 0 | Native records/view |
| Batches | records | 1 | 0 | Native records/view |
| Nutrient Media | records | 1 | 0 | Native records/view |
| Bioreactors | records | 1 | 0 | Native records/view |
| Environment | records | 1 | 0 | Native records/view |
| Yields | records | 1 | 0 | Native records/view |
| Costs | records | 1 | 0 | Native records/view |
| Quality | records | 1 | 0 | Native records/view |
| Contamination | records | 1 | 0 | Native records/view |
| History | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Sensor dashboard | records | 1 | 0 | Native records/view |
| Optimization | records | 1 | 0 | Native records/view |
| Contamination risk | records | 1 | 0 | Native records/view |
| Yield prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sop generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Batch comparison | records | 1 | 0 | Native records/view |
| Strain performance predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality anomaly detect | records | 1 | 0 | Native records/view |
| agentic process optimization | records | 1 | 0 | Native records/view |
| contamination risk early warning | records | 1 | 0 | Native records/view |
| scale up protocol generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| media optimization ensemble | records | 1 | 0 | Native records/view |
| cross batch learning | records | 1 | 0 | Native records/view |
| strains without strain | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| quality without quality | records | 1 | 0 | Native records/view |
| costs without cost | records | 1 | 0 | Native records/view |
| real scada industrial iot integration only manu | integration | 1 | 0 | Provider request records only |
| integration with analytical labs hplc mass spec | integration | 1 | 0 | Provider request records only |
| integration with downstream processing purifica | integration | 1 | 0 | Provider request records only |
| limited regulatory documentation cgmp fda complian | records | 1 | 0 | Native records/view |
| webhooks for alert delivery | integration | 1 | 0 | Provider request records only |
| mobile app for operators | records | 1 | 0 | Native records/view |
| limited notifications layer | records | 2 | 0 | Native records/view |
| Predictive Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Work Orders | records | 1 | 0 | Native records/view |
| Failure Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment Health | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| What-If Simulator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sensor Monitor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Parts Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Window Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Alert Fatigue | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Work Order Priority | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maint. Recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Failure Root Cause | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance ROI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| OEE Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive Parts | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Spare Parts | records | 1 | 0 | Native records/view |
| Cost Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Users | records | 1 | 0 | Native records/view |
| Lube Compliance | records | 1 | 0 | Native records/view |
| Asset Registry+ | records | 1 | 0 | Native records/view |
| Sensor Ingestion | records | 1 | 0 | Native records/view |
| Anomaly Events | records | 1 | 0 | Native records/view |
| Predictive Scheduling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generated WOs | records | 1 | 0 | Native records/view |
| Parts Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Downtime & ROI | records | 1 | 0 | Native records/view |
| Tech Checklists | records | 1 | 0 | Native records/view |
| Live Anomalies | records | 1 | 0 | Native records/view |
| Agentic maintenance orchestration | records | 1 | 0 | Native records/view |
| Digital twin simulation | records | 1 | 0 | Native records/view |
| Anomaly streaming | records | 1 | 0 | Native records/view |
| Maintenance ROI calculator | records | 1 | 0 | Native records/view |
| Alerts without `/alert | records | 1 | 0 | Native records/view |
| Workorders without `/workorder | records | 1 | 0 | Native records/view |
| No `/digital | records | 1 | 0 | Native records/view |
| CMMS, IoT, OEE modules exist but real third | records | 1 | 0 | Native records/view |
| No integration with asset management (purchase, depreciation) | integration | 1 | 0 | Provider request records only |
| No mobile app for field technicians (grep 0 react | records | 1 | 0 | Native records/view |
| No webhooks for external systems | integration | 1 | 0 | Provider request records only |
| Missing features | records | 1 | 0 | Native records/view |
| Production readiness | records | 1 | 0 | Native records/view |
| Robots | records | 1 | 0 | Native records/view |
| Zones | records | 1 | 0 | Native records/view |
| Collisions | records | 1 | 0 | Native records/view |
| Operators | records | 1 | 0 | Native records/view |
| Task allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collision avoidance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Path planning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Throughput optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Simulation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Auto dispatch | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Oee | records | 1 | 0 | Native records/view |
| Battery optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Zone heat map | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fault diagnosis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Robot health dashboard | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance benchmarking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dynamic fleet sizing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Zone capacity forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Charging orchestration | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| dynamic fleet size optimization | records | 1 | 0 | Native records/view |
| predictive collision prevention | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| zone capacity forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| robot specialization learning | records | 1 | 0 | Native records/view |
| autonomous charging orchestration | records | 1 | 0 | Native records/view |
| failure mode learning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| batteryoptimization charge scheduling | records | 1 | 0 | Native records/view |
| zoneheatmap bottleneck identification | records | 1 | 0 | Native records/view |
| robothealthdashboard aggregate health met | records | 1 | 0 | Native records/view |
| performancebenchmarking ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| faultdiagnosis rootcause from telemetry | records | 1 | 0 | Native records/view |
| fleet visualizationmapping realtime posit | records | 1 | 0 | Native records/view |
| robot devicedriverros integration | integration | 1 | 0 | Provider request records only |
| zonelayout management ui route | records | 1 | 0 | Native records/view |
| telemetry ingestion endpoint sensor strea | records | 1 | 0 | Native records/view |
| wmserp integration sap manhattan | integration | 1 | 0 | Provider request records only |
| notifications for critical faults | records | 1 | 0 | Native records/view |
| audit log for safetyrelated interventions | records | 1 | 0 | Native records/view |
| Products | records | 1 | 0 | Native records/view |
| Inspections | records | 1 | 0 | Native records/view |
| Defects | records | 1 | 0 | Native records/view |
| Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Defect classifier | records | 1 | 0 | Native records/view |
| Severity scorer | records | 1 | 0 | Native records/view |
| Root cause | records | 1 | 0 | Native records/view |
| Trend tracker | records | 1 | 0 | Native records/view |
| Quality inspector | records | 1 | 0 | Native records/view |
| Packaging optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Report generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Batch inspection | records | 1 | 0 | Native records/view |
| Defect trend analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reinspection scheduler | records | 1 | 0 | Native records/view |
| Mes alerts | records | 1 | 0 | Native records/view |
| Predictive quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Improvement recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier quality score | records | 1 | 0 | Native records/view |
| Defect parameter correlation | records | 1 | 0 | Native records/view |
| Spc control chart | records | 1 | 0 | Native records/view |
| computer vision defect detector running on line cameras | records | 1 | 0 | Native records/view |
| predictive quality scoring flagging at risk production runs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| root cause correlation tying defects to process parameters | records | 1 | 0 | Native records/view |
| supplier quality tracking scoring supplier defect contributions | records | 1 | 0 | Native records/view |
| process change recommendation engine reducing defect rates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| direct mes erp integration for closed loop quality control | integration | 1 | 0 | Provider request records only |
| computer vision for direct defect detection from | records | 1 | 0 | Native records/view |
| predictive quality scoring for upcoming production runs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| automated root cause correlation ml | records | 1 | 0 | Native records/view |
| real time spc statistical process control visualization | records | 1 | 0 | Native records/view |
| erp integration for rework scrap tracking | integration | 1 | 0 | Provider request records only |
| supplier quality management module | records | 1 | 0 | Native records/view |
| webhooks for mes events beyond the alert | integration | 1 | 0 | Provider request records only |
| notifications subsystem | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 400 feature pages were visited in the browser; 398 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 186 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

186 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
