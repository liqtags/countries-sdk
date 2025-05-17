# Countries SDK

A simple TypeScript SDK providing a comprehensive list of countries with their ISO 3166-1 alpha-2 codes.

## Usage

```typescript
// Get all countries
const allCountries = Countries;

// Find a specific country by ISO code
const usa = Countries.find(country => country.id === 'US');

// Find a country by name
const japan = Countries.find(country => country.label === 'Japan');
```

## Data Structure

Each country object in the array has the following structure:

```typescript
interface Country {
  label: string;  // Full country name
  id: string;     // ISO 3166-1 alpha-2 code
}
```

## Features

- Complete list of 249 countries and territories
- ISO 3166-1 alpha-2 codes for each country
- TypeScript support with built-in types
- Zero dependencies
- Lightweight and easy to use

## List of Included Countries

The SDK includes all internationally recognized sovereign states and dependent territories, including:

- All UN member states
- All UN observer states
- All dependent territories
- Special administrative regions
- Overseas territories

## Validation

The country list has been validated against:
- ISO 3166-1 standard
- UN member states list
- Common dependent territories
