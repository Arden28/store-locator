SeaBar Locations Code Explanation

This HTML file creates an interactive webpage displaying SeaBar retail and cleanup locations on a Google Map.

- HTML Structure:
  - Displays a trash counter bar showing total pounds of ocean trash cleaned.
  - Includes a search bar, radius selector (10-100 miles), and filters for Retailer/Cleanup Site.
  - Renders a Google Map and a scrollable list of location cards.

- CSS Styling:
  - Uses Poppins font, a clean layout with a light background.
  - Styles the trash counter with a gradient and hover effect.
  - Implements a responsive control row with flexbox, stacking vertically on mobile.
  - Customizes map, location cards, and info windows with shadows and rounded corners.
  - Media queries adjust font sizes and layouts for screens <768px and <480px.

- JavaScript Functionality:
  - Initializes a Google Map with custom styles, centered on the US.
  - Fetches location data from a Google Script endpoint.
  - Filters locations by search query, radius, and type (Retailer/Cleanup Site).
  - Uses Google Maps Geocoding for address searches and MarkerClusterer for grouping markers.
  - Displays location details in info windows and cards, with clickable titles to zoom on the map.
  - Updates the trash counter by summing "Pounds Cleaned" from cleanup sites.
  - Debounces search input and map bounds changes for performance.

The code ensures a responsive, user-friendly interface with error handling for robust operation.

For any further questions or support, feel free to reach out to me

Name: Arden BOUET
Phone: +254745908026
Email: laudbouetoumoussa@gmail.com

Looking foward to hear from you!