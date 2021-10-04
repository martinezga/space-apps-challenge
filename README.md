# 🚀️ space-apps-challenge

## 🌞️ You are my Sunshine

**Backend API made with Django, Docker and Docker-compose.**

It's an open source application to access the information on NASA’s Prediction of Worldwide renewable Energy Resources (POWER) web services portal and provide useful information about sunshine to the general public.

### **API URL:** https://spaceappssunshineback.azurewebsites.net/api/

**Example response: (you could change this parameters for your own)** https://spaceappssunshineback.azurewebsites.net/api/nasa/?start=2020&end=2020&latitude=10.4880100&longitude=-66.8791900&resolution=monthly&comunity=sb

### **Challenge:**
https://2021.spaceappschallenge.org/challenges/statements/you-are-my-sunshine/details

### **Usage**:

**Required params:**

```
{
    'start': YYYYMMDD,
    'end': YYYYMMDD,
    'latitude': grades,
    'longitude': grades,
    'resolution': temporal timeframe,
    'comunity': unit,
}
resolution can be hourly, daily, weekly, monthly, yearly
community can ag, sb, re 
```


**Example Endpoint**
- api/nasa/?start=20200101&end=20201201&latitude=10.4880100&longitude=-66.8791900&resolution=monthly&comunity=sb

**Source code**
- Create a dotenv file like the example one.
- Run:

```
sudo docker-compose up --build
```

or
```
sudo docker-compose  -f docker-compose-dev.yml  up --build
```

- 😁️ Enjoy!

### **API used:**
https://power.larc.nasa.gov/api/pages/

Parameter dictionary -> https://power.larc.nasa.gov/#resources

---

## 💝️ Thanks to [Francisco Rocha](!https://github.com/fcoalerocha) who help us during all the challenge! Even at code night time! 🤪️

---
⌨️ con ❤️ por [Gabriella Martínez](https://github.com/martinezga) 😊
