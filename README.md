# 📺 Company Wall

Your All-in-One Organization Dashboard

Company Wall is a dynamic and visually engaging dashboard that brings your organization to life by aggregating essential information in real-time. Built with Blazor, MudBlazor, and .NET 9, Company Wall is your go-to tool for monitoring GitHub activity, tracking team presence, staying updated with the weather, and celebrating milestones.

🌟 Features
- 📊 Real-Time GitHub Insights: View commits, contributors, and repository activity across your organization.
- 🟢 MS Teams Presence Integration: Displays the current status (Available, Busy, Away, etc.) of your team members.
- 🌤️ Weather Updates: Keep an eye on local weather conditions for your team’s locations.
- 🎉 Upcoming Celebrations: Never miss birthdays, work anniversaries, or other key events.
- 🎨 Modern UI: Powered by MudBlazor, ensuring a responsive and user-friendly experience.
- ⚙️ Customizable Configuration: Manage all settings via the appsettings.json file for seamless integration with your environment.

🎯 Use Cases
- Organization Leaders: Gain instant visibility into team status, GitHub activities, and key milestones.
- Team Members: Stay informed about the latest commits, weather, and upcoming events.
- Event Planners: Monitor and prepare for celebrations within the organization.

🛠️ Tech Stack
- Frontend: Blazor, MudBlazor
- Backend: .NET 9
- Integrations:
- GitHub REST API
- Microsoft Graph API (for MS Teams presence)
- OpenWeather API (for weather updates)
- Configuration: appsettings.json

🚀 Getting Started

Follow these steps to set up Company Wall locally:

Prerequisites
- .NET 9 SDK
- A GitHub Personal Access Token with repo and read:org permissions.
- A Microsoft Graph API Token with Presence.Read.All permission.
- A OpenWeather API Key.

Installation

- Clone the Repository:

```
git clone https://github.com/kasuken/companywall.git
cd companywall
```

- Configure Application Settings:
Open the appsettings.json file in the root of the project and configure your API keys and settings:

```
{
  "GitHub": {
    "PersonalAccessToken": "your-github-pat"
  },
  "MicrosoftGraph": {
    "ClientId": "your-client-id",
    "TenantId": "your-tenant-id",
    "ClientSecret": "your-client-secret"
  },
  "OpenWeather": {
    "ApiKey": "your-openweather-api-key",
    "City": "your-city"
  },
  "Celebrations": {
    "Events": [
      { "Name": "John's Birthday", "Date": "1985-12-01" },
      { "Name": "Company Anniversary", "Date": "2024-01-15" }
    ]
  }
}
```

- Run the Application:

```
dotnet build
dotnet run
```

- Open your browser and navigate to http://localhost:5000.

🎨 Screenshots

Coming Soon

🧑‍💻 Contributing

We welcome contributions from developers of all levels! 🛠️

Please read our Contributing Guide for more details.

📝 License

This project is licensed under the MIT License.

💬 Contact & Support

- GitHub Issues: Open an Issue

Stay connected and help us improve Company Wall!

⭐ Star Us!

If you find Company Wall helpful, please give a ⭐ on GitHub to show your support and help others discover this project!

📚 Resources

- Blazor Documentation
- MudBlazor Documentation
- GitHub REST API
- Microsoft Graph API
- OpenWeather API
