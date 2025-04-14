# North Carolina Permitted Animal Facilities (2024) and County Population (2023) Bivariate Map
This map depicts bivariate symbolization using point and area level data in the web mapping environment. It represents North Carolina permitted animal facilities overalaid with county population estimates. In North Carolina, concentrated animal feeding operations (CAFOs), a type of permitted animal facility, are typically located in low populated, historically underesourced communities of color. Chloropleth symbolization and the chroma.js library are used to visulize and better understand the number of permitted animal facilities and its association to county population. Placemarker visualization of each animal facility location is depicted using the Font Awesome icon library and chroma.js library for categorical difference in animal facility type. A custom Leaflet control is used to create the legend showing the chloropleth sequential color pallete and categorical animal facility types. 
# Packages, Stylesheets, and Data
- **Leaflet.js**: map creation and customization
- **jQuery**: handling DOM manipulation and event handling
- **Leaflet.css and Google Fonts**: stylesheets for the design of the user interface
- **FontAwesome**: custom icons
- **Chroma.js**: color conversions and scales

**Data provided by:** (1) [North Carolina Department of Environmental Quality](https://www.deq.nc.gov/about/divisions/water-resources/permitting/animal-feeding-operations/animal-facility-map) for permitted animal facilites and (2) [North Carolina Office of State Budget and Management](https://linc.osbm.nc.gov/explore/dataset/county_estimates/table/?flg=en-us&disjunctive.area_type&disjunctive.area&refine.population_estimate=2023&refine.area_type=County&sort=value) for county population estimates. 
