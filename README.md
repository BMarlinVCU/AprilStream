# Interactive Advertising Data Dashboard

This Google Colab notebook provides an interactive dashboard built with Gradio to visualize and filter advertising spend data across different cities.

## Project Description

This project analyzes advertising expenditure across various media (TV, Radio, Newspaper) and its correlation with sales in different cities. It leverages Plotly for interactive map visualizations and Gradio for creating a user-friendly web interface.

The dashboard allows users to:
- Filter the dataset based on minimum and maximum spend for TV, Radio, and Newspaper.
- Visualize advertising spend on a map, with the size of the markers representing the selected metric (TV, Radio, or Newspaper) and color indicating sales.

## Dataset

The dataset used in this notebook is `Advertising_F.csv`, which contains information on:
- `TV`: Advertising spend on TV.
- `radio`: Advertising spend on radio.
- `newspaper`: Advertising spend on newspapers.
- `sales`: Total sales.
- `City`: The city where the advertising took place.
- `latitude`, `longitude`: Geographical coordinates of the city.

## How to Run the Notebook

1.  **Open in Google Colab**: Click on the "Open in Colab" badge (if provided, or simply open the `.ipynb` file in Colab).
2.  **Run all cells**: Go to `Runtime > Run all` in the Colab menu.
3.  **Access the Gradio Dashboard**: Once all cells have executed, a Gradio interface will launch, providing a public URL (e.g., `https://xxxx.gradio.live`). Click on this URL to open the interactive dashboard.

## Using the Gradio Dashboard

The dashboard features:
-   **Sliders for TV, Radio, Newspaper Min/Max**: Adjust these sliders to filter the data based on your desired advertising spend ranges.
-   **Map Metric (Size) Radio Buttons**: Select whether you want the size of the markers on the map to represent 'TV', 'radio', or 'newspaper' spend.
-   **Filtered Data Table**: A table displaying the data rows that match your filtering criteria.
-   **Advertising Spend Map**: An interactive map showing the cities. The size of each city's marker corresponds to the selected map metric, and the color represents the sales.

Enjoy exploring the advertising data interactively!
