import pandas as pd
import matplotlib.pyplot as plt

# Data from the image
data = {
    'Year': [2022, 2023, 2024, 2025],
    'Incidents': [567, 558, 616, 550],
    'User Requests': [1850, 2144, 3780, 5000],
    'Alerts': [4800, 6000, 13000, 12500],
    'Infra Cost': [2500, 3000, 3600, 4000],
    'Unique Users to Podium': [2071, 3958, 7025, 16000],
    'Controls & MI': [173, 197, 230, 500]
}

# Create a DataFrame
df = pd.DataFrame(data)

# Plot Line Charts for Time-based Trends
fig, axs = plt.subplots(3, 2, figsize=(14, 10))

# Incidents
axs[0, 0].plot(df['Year'], df['Incidents'], marker='o', color='b')
axs[0, 0].set_title('Incidents Over Time')
axs[0, 0].set_xlabel('Year')
axs[0, 0].set_ylabel('Incidents')

# User Requests
axs[0, 1].plot(df['Year'], df['User Requests'], marker='o', color='g')
axs[0, 1].set_title('User Requests Over Time')
axs[0, 1].set_xlabel('Year')
axs[0, 1].set_ylabel('User Requests')

# Alerts
axs[1, 0].plot(df['Year'], df['Alerts'], marker='o', color='r')
axs[1, 0].set_title('Alerts Over Time (in hundreds)')
axs[1, 0].set_xlabel('Year')
axs[1, 0].set_ylabel('Alerts (hundreds)')

# Infra Cost
axs[1, 1].plot(df['Year'], df['Infra Cost'], marker='o', color='m')
axs[1, 1].set_title('Infra Cost Over Time (in thousands)')
axs[1, 1].set_xlabel('Year')
axs[1, 1].set_ylabel('Infra Cost (Thousands)')

# Unique Users to Podium
axs[2, 0].plot(df['Year'], df['Unique Users to Podium'], marker='o', color='orange')
axs[2, 0].set_title('Unique Users to Podium Over Time')
axs[2, 0].set_xlabel('Year')
axs[2, 0].set_ylabel('Unique Users')

# Controls & MI
axs[2, 1].plot(df['Year'], df['Controls & MI'], marker='o', color='purple')
axs[2, 1].set_title('Controls & MI Over Time')
axs[2, 1].set_xlabel('Year')
axs[2, 1].set_ylabel('Controls & MI')

plt.tight_layout()
plt.show()



ere are the line charts representing time-based trends for each category from 2022 to 2025:

Incidents Over Time: Shows a slight decrease in 2023, followed by a peak in 2024, then a drop in 2025.
User Requests Over Time: Steady increase each year, with a notable jump in 2024 and 2025.
Alerts Over Time: A significant rise from 2022 to 2024, with a slight decrease in 2025.
Infra Cost Over Time: Gradual and consistent rise in infrastructure costs each year.
Unique Users to Podium Over Time: Steep increase, particularly between 2024 and 2025.
Controls & MI Over Time: Gradual increase, with a sharp rise between 2024 and 2025.
