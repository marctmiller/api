api
===

Quick and dirty API docs. We will attempt to follow [jsonapi](http://jsonapi.org/) standards 
using RABL via [these guidelines](https://github.com/nesquena/rabl/wiki/Conforming-to-jsonapi.org-format)

`/fund-treatments.json`

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
  ]
}
```
