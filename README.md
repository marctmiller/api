api
===

Quick and dirty API docs. We will attempt to follow [jsonapi](http://jsonapi.org/) standards 
using RABL via [these guidelines](https://github.com/nesquena/rabl/wiki/Conforming-to-jsonapi.org-format)

`GET /fund-treatments.json`

```javascript
{
  profiles: 
  [
    {
      id: 387,
      token: "69a1b67ff206",
      name: "Corine",
      age: 9,
      country: "Nepal",
      promo_description: "Doloribus voluptas repudiandae cum sunt quo.",
      url: "https://watsi.org/profile/69a1b67ff206-corine",
      badge_url: "https://cdn.watsi.org/uploads/profile/image/387/badge_original-profile.jpg",
      profile_url: "https://cdn.watsi.org/uploads/profile/image/387/profile_original-profile.jpg",
      per_cent_funded: "74%",
      target: "$150",
      target_to_go: "$39 to go",
      donated: "$111",
      number_of_donors: 19
    }
  ],
  funds:
  [
    {
      id: 1,
      token: "universal",
      name: "Universal Fund",
      promo_description: "100% of your donation funds medical care for patients around the world.",
      url: "https://watsi.org/funds/universal-fund",
      badge_url: "https://d3w52z135jkm97.cloudfront.net/uploads/fund/image/1/badge_UF6002.jpg",
      profile_url: "https://d3w52z135jkm97.cloudfront.net/uploads/fund/image/1/profile_UF6002.jpg",
      number_of_donors: 65
    }
  ]
}
```
