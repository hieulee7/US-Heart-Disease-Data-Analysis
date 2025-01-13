# US Heart Disease Analytics Platform

A cloud-based healthcare analytics solution leveraging Google Cloud Platform to process and visualize cardiovascular disease risks across the United States. The platform combines data warehousing capabilities with interactive dashboards to transform nationwide health survey data into actionable insights.

## Problem Statement
Healthcare organizations face significant challenges in:
- Processing multi-dimensional health data at scale
- Identifying demographic risk patterns for resource allocation
- Quantifying lifestyle factors' impact on heart health  
- Evaluating preventive care effectiveness across populations

This platform bridges these gaps by providing role-specific analytics dashboards powered by automated data processing pipelines.

## Implementation Details

### Data Ingestion & Processing
- **Source**: CDC's Behavioral Risk Factor Surveillance System (BRFSS) with 246,000+ survey responses
- **Infrastructure**: Google Cloud BigQuery serverless architecture
- **ETL Pipeline**:
 - Initial data upload with clustering optimization for frequent queries
 - SQL transformations for demographic segmentation and risk calculations
 - Automated scheduling for real-time data updates

### Data Warehouse Architecture
- **Schema Design**: Optimized for healthcare metrics analysis
- **Key Tables**:
 - Demographic indicators
 - Lifestyle behaviors  
 - Preventive care metrics
 - Risk factor calculations
- **Performance**: Columnar storage format with query optimization

### Dashboard Implementation
1. **Demographic Analysis Dashboard**:
   - Geographic distribution via dot plot map
   - Age/gender breakdown charts
   - Race/ethnicity segmentation
   - Cross-filtering capabilities

2. **Lifestyle Impact Dashboard**:
   - Behavioral correlation analysis
   - Sleep pattern impact visualization  
   - Physical activity tracking
   - Risk score calculations

3. **Preventive Care Dashboard**:
   - Intervention effectiveness metrics
   - Vaccination impact analysis
   - Regular checkup correlations
   - Population group comparisons

### Security Features
- Role-based access control (RBAC)
- Data encryption at rest and in transit
- Audit logging for compliance
- Secure credential management

## Tech Stack Details
- **Data Processing**: Google Cloud BigQuery
 - Serverless SQL queries
 - Automated data transformations
 - Scheduled updates
 
- **Visualization**: Looker Studio
 - Interactive filtering
 - Real-time updates
 - Cross-dashboard linking
 - Custom chart types

- **Data Source Integration**:
 - CSV data ingestion
 - Automated quality checks
 - Schema validation

## Installation & Access

### BigQuery Project Access
- Refer to the provided credential and cloud project ID provided in the document

### Dashboard Access
Public View URL: [US Heart Disease Dashboard](https://lookerstudio.google.com/reporting/5608abd6-c6c9-436b-965e-b742a8c57f44)

### Development Setup
1. Clone repository
2. Configure GCP credentials
3. Set up BigQuery access
4. Connect Looker Studio

## Usage Examples

### For Public Health Officials
1. Access Demographic Dashboard
2. Filter by state/region
3. Analyze population segments
4. Export visualizations

### For Medical Researchers
1. Use Lifestyle Impact Dashboard
2. Examine correlation patterns
3. Filter by behavioral factors
4. Generate research insights

### For Healthcare Providers
1. Navigate to Preventive Care Dashboard
2. Track intervention effectiveness
3. Compare population groups
4. Export metrics reports

## Future Enhancements
- Machine learning integration for risk prediction
- Real-time health data streaming
- Additional visualization types
- Enhanced mobile responsiveness
- API development for external integration
