# Facts About India 🍛 🧘  🇮🇳

+ An API that will return random Facts About India 
+ Dedicated To All Who ❤️ INDIA

## Usage:

+ ### [`https://factsaboutindiaapi.herokuapp.com/`](https://factsaboutindiaapi.herokuapp.com/) to get the documentation.
+ ### [`https://factsaboutindiaapi.herokuapp.com/api/Random-Facts/all`](https://factsaboutindiaapi.herokuapp.com/api/Random-Facts/all) to get all the Food Names at once.
+ Change `all` to parameter `?number=` to specify the number of Food Names you want to receive.
+ Change `all` to parameter `?index=` to specify the index of the Food Name you are targeting.

This project is hosted by [Heroku](https://www.heroku.com/) with with jlcpcbofficial@gmail.com

## Rebuild the project:
+ Clone the repo.
+ Run `python -m venv .env` to create a virtual environment.
+ Run `source .env/bin/activate` to activate the virtual environment.
+ Run `pip install requirements.txt`.
+ Run `python app.py`.
+ App starts at `http://localhost:5000` by default, but can be configured with a `.env` file. 

## Example:

+ ### [`https://factsaboutindiaapi.herokuapp.com/api/Random-Facts?number=1`](https://factsaboutindiaapi.herokuapp.com/api/Random-Facts?number=1) returns: ↓
```JSON
[
{
"Fact-About-India": "World's First Hospital Train Is In India"
}
]
```

+ ### [`https://factsaboutindiaapi.herokuapp.com/api/Random-Facts?number=2`](https://factsaboutindiaapi.herokuapp.com/api/Random-Facts?number=1) returns: ↓
```JSON
[
{
"Fact-About-India": "Indian National Kabaddi Team Has Won all World Cups"
},
{
"Fact-About-India": "The Origin of Ayurveda and Yoga"
}
]
```
