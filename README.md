import pandas as pd
import matplotlib.pyplot as plt

# Updated data with 2026 values
data = {
    'Year': [2022, 2023, 2024, 2025, 2026],
    'Incidents': [567, 558, 616, 550, 495],
    'User Requests': [1850, 2144, 3780, 5000, 4500],
    'Alerts': [480, 600, 1300, 1250, 1200],
    'Infra Cost': [2500, 3000, 3600, 4000, 4500],
    'Unique Users to Podium': [2071, 3958, 7025, 16000, 25000],
    'Tech risk findings': [84, 134, 226, 134, 168],
    'Controls & MI': [173, 197, 230, 500, 800]
}

# Create a DataFrame
df = pd.DataFrame(data)

# Create a single combined chart
plt.figure(figsize=(12, 8))

# Plot each metric on the same chart with different styles
plt.plot(df['Year'], df['Incidents'], marker='o', label='Incidents', color='b')
plt.plot(df['Year'], df['User Requests'], marker='o', label='User Requests', color='g')
plt.plot(df['Year'], df['Alerts'], marker='o', label='Alerts (hundreds)', color='r')
plt.plot(df['Year'], df['Infra Cost'], marker='o', label='Infra Cost (Thousands)', color='m')
plt.plot(df['Year'], df['Unique Users to Podium'], marker='o', label='Unique Users to Podium', color='orange')
plt.plot(df['Year'], df['Tech risk findings'], marker='o', label='Tech Risk Findings', color='c')
plt.plot(df['Year'], df['Controls & MI'], marker='o', label='Controls & MI', color='purple')

# Add titles and labels
plt.title('Combined Business Metrics (2022-2026)')
plt.xlabel('Year')
plt.ylabel('Counts/Values')
plt.xticks(df['Year'])  # Set x-ticks to the years
plt.legend()
plt.grid()

# Save the figure
plt.savefig('combined_business_metrics.png')

# Show the plot
plt.show()
