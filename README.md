# Ship Fuel Efficiency Dataset

## Overview

This dataset contains comprehensive information about ship fuel consumption, CO₂ emissions, and operational efficiency across various vessel types and routes in Nigerian waters. The data spans one full year (January-December) and includes 99 unique ships with detailed monthly operational records.

## Dataset Structure

- **Total Records**: 1,188 monthly observations
- **Time Period**: 12 months (January - December)
- **Unique Ships**: 99 vessels (NG001 through NG099)
- **File Format**: Excel (.xlsx)
- **Sheet Name**: `ship_fuel_efficiency`

## Columns Description

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| `ship_id` | String | Unique identifier for each vessel (e.g., NG001, NG002) |
| `ship_type` | String | Type of vessel: Oil Service Boat, Fishing Trawler, Surfer Boat, Tanker Ship |
| `route_id` | String | Shipping route: Warri-Bonny, Port Harcourt-Lagos, Escravos-Lagos, Lagos-Apapa |
| `month` | String | Month of operation (January through December) |
| `distance` | Numeric | Distance traveled (in nautical miles or kilometers) |
| `fuel_type` | String | Type of fuel used: HFO (Heavy Fuel Oil) or Diesel |
| `fuel_consumption` | Numeric | Amount of fuel consumed (liters or tons) |
| `CO2_emissions` | Numeric | Carbon dioxide emissions (kg or tons) |
| `weather_conditions` | String | Weather during voyage: Stormy, Moderate, Calm |
| `engine_efficiency` | Numeric | Engine efficiency percentage (70-95%) |

## Key Statistics

### Ship Type Distribution
- **Oil Service Boat**: Multiple vessels serving oil industry
- **Fishing Trawler**: Commercial fishing vessels
- **Surfer Boat**: Smaller passenger/cargo vessels
- **Tanker Ship**: Large fuel and cargo transport vessels

### Route Information
- **Warri-Bonny**: Key oil-producing region route
- **Port Harcourt-Lagos**: Major commercial corridor
- **Escravos-Lagos**: Coastal shipping route
- **Lagos-Apapa**: Major port access route

### Operational Metrics Range
- **Distance**: 20.58 - 498.18 units
- **Fuel Consumption**: 237.88 - 24,648.52 units
- **CO₂ Emissions**: 615.68 - 65,937.46 units
- **Engine Efficiency**: 70.01% - 94.95%

## Potential Use Cases

1. **Fuel Efficiency Analysis**: Compare fuel consumption across ship types and routes
2. **Environmental Impact**: Study CO₂ emissions patterns
3. **Operational Optimization**: Identify factors affecting engine efficiency
4. **Route Planning**: Analyze distance and weather impact on fuel usage
5. **Maintenance Scheduling**: Correlate engine efficiency with operational patterns

## Data Quality Notes

- Complete dataset with no apparent missing values
- Consistent formatting across all records
- Realistic value ranges for all numerical fields
- Balanced distribution across months and ship types

## Limitations

- Specific units for distance, fuel consumption, and emissions not explicitly stated
- No information about ship size, age, or cargo capacity
- Weather conditions are categorical without quantitative measures

## Suggested Analysis Approaches

1. **Time Series Analysis**: Monthly trends in fuel efficiency
2. **Comparative Analysis**: Ship type performance differences
3. **Correlation Studies**: Relationship between distance, fuel consumption, and emissions
4. **Weather Impact**: Effect of weather conditions on operational metrics
5. **Route Optimization**: Identify most fuel-efficient routes

This dataset provides valuable insights for maritime operations, environmental monitoring, and transportation efficiency studies in the West African maritime sector.# Ship-Fuel-Efficiency
