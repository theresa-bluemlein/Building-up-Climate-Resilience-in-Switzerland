# Welcome to the challenge on "Building-up resilience against extreme weather events in Switzerland" by Swiss Re
This respository is part of the Zurich hackathon of [Swiss {ai} Week](https://swiss-ai-weeks.ch/) happening on 26/27 September 2025.

By accessing or using the data provided, you agree to the following terms and conditions.
## Terms and Conditions
> The data is provided solely for the purpose of participating in the hackathon event held in Zurich, Switzerland, and for developing solutions directly related to the specific challenge you have selected. You are strictly prohibited from using the Data for any other purpose, including but not limited to:
> - Commercial use.
> - Research or development outside the scope of this hackathon challenge.
> - Personal use or any other unauthorized activities.
> 
> The data is provided "as is" without any warranties, express or implied, including but not limited to, warranties of merchantability, fitness for a particular purpose, or non-infringement. The hackathon organizers do not guarantee the accuracy, completeness, or reliability of the data.
>
> Immediately following the conclusion of the hackathon event, you are obligated to permanently and securely delete all copies of the data, including any derived or processed data, from all your devices, storage media, and systems. 

## Source of Data
The data of this respository has been provided by [Swiss Re](https://www.swissre.com/)

# Hackathon – Open Data Access
Welcome to the Hackathon on **AI for Resilience against Extreme Weather Events**!  
In this challenge, you will use **open-source weather and climate data from MeteoSwiss** to build AI-powered solutions that help society become more resilient against **extreme weather events in Switzerland**.  

Your solutions might include:
- **Innovative Parametric Insurance Solutions**: Design and prototype a parametric insurance model with innovative trigger mechanism based on real-time environmental data (e.g. extreme temperature index). Simulate payout scenarios based on historical or synthetically created datasets. The payout does not need to be financial - think of what would bring instant relief to society, e.g. during a heatwave! 
- **AI-Powered Early Warning Systems**: Thinking of individuals living or travelling through Switzerland, design and prototype an AI-powered application enabling to better apprehend selected risks (e.g., landslides or glacier collapses) and issuing warnings or relevant mitigation recommendations based on the user location. The AI model should be able to leverage multimodal data ranging from weather to topological data and assume the user's location as known. 
- **Intelligent Disaster Response Systems** Prototype a platform for real-time disaster coordination with integration of open source exposure data and optimized resource allocation in case of a disaster. Conduct damage assessment of natural hazards (e.g., floods, hail, windstorms, precipitation) on properties from street view or satellite imagery. The tool should help identify where the most significant losses/damage might occur. For example, in areas with high concentration of rooftop solar panels, older and more vulnerable buildings, or other exposure characteristics that increase susceptibility to damage.   


To get started, you will need open source weather and climate data.  

---

## 📊 Data Sources

We will use the **official MeteoSwiss open data**.  
You have two main options to access it:

---

### 1. Download Manually (No Coding Required)

MeteoSwiss provides an easy interface for downloading datasets in **CSV** or **TXT** format:

👉 [MeteoSwiss Data Download Portal](https://www.meteoswiss.admin.ch/services-and-publications/applications/ext/download-data-without-coding-skills.htm)

From there, you can:
- Select different meteorological parameters (temperature, precipitation, sunshine, wind, etc.)
- Choose a station and timeframe
- Export the data directly

We’ve also added a **few sample CSVs** in this repository (`/data` folder) so you can quickly test your pipelines.

---

### 2. Access via API (Programmatic Access)

For automated workflows and larger projects, you can fetch data using the **MeteoSwiss Opendata API**.
📖 Documentation: [MeteoSwiss Opendata GitHub](https://github.com/MeteoSwiss/publication-opendata)

Key features:
- REST-like API  
- Data available in **JSON, CSV, and XML**  
- Includes observations, forecasts, and gridded datasets

