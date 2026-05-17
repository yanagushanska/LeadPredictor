# LeadPredictor

A lead prediction calculator designed to help you estimate the number of prospects, leads, and customers needed to achieve your business revenue goals.

## Overview

LeadPredictor is an interactive web application that uses three mathematical formulas to calculate the required customer acquisition metrics based on your total revenue target and average order value. It helps you understand the relationship between your revenue goals and the customer pipeline you need to build.

## Features

- **Three-Step Calculation Formula** - Automatically calculates prospects, leads, and customers needed
- **Real-Time Updates** - Response rate sliders provide instant recalculation
- **Input Validation** - Prevents calculations until all required fields are filled
- **Dark Theme Dashboard** - Modern, professional interface with visual metrics cards
- **Responsive Design** - Works on desktop and mobile devices

## How to Use

1. **Fill in the Campaign Details:**
   - **Campaign Start** - Select the start date for your campaign
   - **Campaign End** - Select the end date for your campaign
   - **Total Revenue** - Enter your target revenue goal (e.g., 10000)
   - **Avg. Order Value** - Enter the average value per customer order (e.g., 100)

2. **Adjust Response Rates:**
   - **Lead Response Rate** - Use the slider to set what percentage of leads convert to customers (0-100%)
   - **Prospect Response Rate** - Use the slider to set what percentage of prospects convert to leads (0-100%)

3. **Click Calculate** - Press the Calculate button to run the analysis

4. **View Results** - The Summary section will display:
   - **Prospects** - Total contacts needed
   - **Leads** - Qualified leads needed
   - **Customers** - Number of customers to reach your revenue goal

## Formulas

### Formula 01: Calculate Required Customers
```
Customers = Total Revenue ÷ Avg. Order Value
```
Determines how many customers you need to acquire to reach your revenue target.

### Formula 02: Calculate Required Leads
```
Leads = Customers × 100 ÷ Lead Response Rate (%)
```
Calculates how many leads you need to generate to convert enough customers, based on your lead-to-customer conversion rate.

### Formula 03: Calculate Required Prospects
```
Prospects = Leads × 100 ÷ Prospect Response Rate (%)
```
Calculates the total number of prospects (initial contacts) needed to generate enough leads, based on your prospect-to-lead conversion rate.

## Example

If you set:
- Total Revenue: $10,000
- Avg. Order Value: $100
- Lead Response Rate: 40%
- Prospect Response Rate: 20%

The calculator will determine:
- **Customers needed:** 100 (10,000 ÷ 100)
- **Leads needed:** 250 (100 × 100 ÷ 40)
- **Prospects needed:** 1,250 (250 × 100 ÷ 20)

This means you need to contact 1,250 prospects to ultimately achieve your $10,000 revenue goal.

## Project Structure

```
LeadPredictor/
├── index.html       # Main HTML file with form and results display
├── style.css        # Styling and layout (dark theme dashboard)
├── README.md        # This file
└── .git/            # Git repository
```

## Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or installation required

## Installation

Simply open `index.html` in your web browser to start using the calculator.

## Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Tips for Best Results

1. **Be Realistic:** Use historical conversion rates from your actual sales pipeline
2. **Test Different Scenarios:** Adjust response rates to see how conversion improvements affect your required prospect count
3. **Regular Updates:** Update your average order value and response rates as your business metrics change
4. **Campaign Planning:** Use the prospect count to determine how many contacts you need in your marketing campaign

## Currency & Language

The calculator currently supports:
- **Currency:** US Dollar ($)
- **Language:** English

Additional currencies and languages can be added through the Language and Currency dropdowns in the interface.

## License

This project is provided as-is for business planning and lead prediction purposes.

## Support

For issues or questions about the application, please refer to the calculation formulas section or verify your input values are realistic for your business model.

---

**Version:** 1.0  
**Last Updated:** May 17, 2026
