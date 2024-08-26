<!-- PROJECT SHIELDS -->
[![Your License](https://img.shields.io/github/license/wanghley/recomendo.svg?style=for-the-badge)](your-license-url)
[![Contributors](https://img.shields.io/github/contributors/wanghley/recomendo.svg?style=for-the-badge)](your-contributors-url)
[![Forks](https://img.shields.io/github/forks/wanghley/recomendo.svg?style=for-the-badge)](your-forks-url)
[![Stargazers](https://img.shields.io/github/stars/wanghley/recomendo.svg?style=for-the-badge)](your-stargazers-url)
[![Issues](https://img.shields.io/github/issues/wanghley/recomendo.svg?style=for-the-badge)](your-issues-url)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555)](your-linkedin-url)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="src/assets/logo-colorful.png" alt="Logo" width="300">
  <h3 align="center">Recomendo</h3>
  <p align="center">
    End-to-end platform aiding small and medium companies, primarily in the food industry, with CRM, lead capture, buyer behavior analysis, and stock management.
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#project-steps">Project Steps</a></li>
    <li><a href="#visualisations">Visualisations</a></li>
    <li><a href="#data-warehouse">Data Warehouse</a></li>
    <li><a href="#future-iterations">Future Iterations</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- PROJECT STEPS -->
## Project Steps

1. **Generating Sales Data**: Creating initial data for a restaurant menu, followed by generating realistic (dummy) sales data for a restaurant chain using Python scripts.
2. **Preparing the Data for a Data Warehouse**: Manipulating the generated data in Python to prepare it for data warehousing.
3. **Data Staging**: Importing data into a PostgreSQL database, staging it, and creating final dimension and fact tables. Adding these tables to the data warehouse and enforcing table constraints.
4. **Visualisations in Tableau Public**: Importing data into Tableau, creating reports and dashboards to track the organization's and individual restaurant's performance on an annual and monthly basis.

<!-- VISUALISATIONS -->
## Visualisations

### Organisation's Annual Performance Dashboard

This dashboard allows users to track the restaurant organization’s performance based on metrics like the number of orders, sales, cost, and profit. It also helps users easily identify which products contribute the most to sales.

![Organisation's Annual Performance Dashboard](https://github.com/vltnnx/Restaurant-Sales-Analysis/blob/main/fig/dashboards/organisation_annual.png?raw=true)

### Restaurants' Monthly Performance Dashboard

Designed for operational managers, this dashboard helps track monthly performance, improving planning for staffing and ingredient stock/purchasing needs.

![Restaurants' Monthly Performance Dashboard](https://github.com/vltnnx/Restaurant-Sales-Analysis/blob/main/fig/dashboards/restaurant_monthly.png?raw=true)

<!-- DATA WAREHOUSE -->
## Data Warehouse

The design of the data warehouse supports efficient data retrieval and analysis.

![Data Warehouse Design](https://github.com/vltnnx/Restaurant-Sales-Analysis/blob/main/fig/data%20warehouse/dwh-design.png?raw=true)

<!-- FUTURE ITERATIONS -->
## Future Iterations

- **Additional Data Generation**: Enhancing the project by generating more data to allow for a more realistic analysis of the organization’s performance, including employee data, working hours, spoilage data, etc.
- **Ingredient Demand Dashboards**: Adding dashboards to analyze ingredient demand, helping restaurants maintain accurate stock levels.

<!-- ROADMAP -->
## Roadmap

- [ ] Develop the recommendation algorithm.
- [ ] Integrate CRM functionalities.
- [ ] Implement stock management features.
- [ ] Expand industry focus beyond the food industry.

See the [open issues](your-issues-url) for a full list of proposed features and known issues.

<!-- CONTRIBUTING -->
## Contributing

Contributions are welcome! If you have suggestions, please fork the repo and create a pull request or open an issue with the tag "enhancement."

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- CONTACT -->
## Contact

Wanghley Soares Martins - [LinkedIn](https://wlinkedin.com/in/wanghley) - me@wanghley.com

Project Link: [https://github.com/wanghley/recomendo](https://github.com/wanghley/recomendo)
