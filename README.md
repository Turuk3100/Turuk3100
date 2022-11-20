- 👋 Hi, I’m @Turuk3100
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Turuk3100/Turuk3100 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
const settings = {
  "async": true,
  "crossDomain": true,
  "url": "https://currency-exchange.p.rapidapi.com/exchange?to=USD&from=EUR&q=1.0",
  "method": "GET",
  "headers": {
    "x-rapidapi-key": "insert-your-unique-rapidapi-key-here",
    "x-rapidapi-host": "currency-exchange.p.rapidapi.com"
  }
};

$.ajax(settings).done(function (response) {
  console.log(response);
});