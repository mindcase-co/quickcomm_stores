# Quick Commerce Store Directory

Store IDs for Indian quick-commerce platforms (Blinkit, Zepto, Swiggy Instamart), grouped by city with pincode and geocoordinates.

These files power the following Apify actors and can be used independently for any integration needing a city→store lookup.

## Files

| Platform | File | Stores | Cities |
|---|---|---|---|
| Blinkit | [`blinkit.json`](./blinkit.json) | 2,100 | 253 |
| Zepto | [`zepto.json`](./zepto.json) | 1,202 | 82 |
| Swiggy Instamart | [`instamart.json`](./instamart.json) | 1,206 | 145 |

## Raw URLs (for programmatic use)

```
https://raw.githubusercontent.com/mindcase-co/quickcomm_stores/main/blinkit.json
https://raw.githubusercontent.com/mindcase-co/quickcomm_stores/main/zepto.json
https://raw.githubusercontent.com/mindcase-co/quickcomm_stores/main/instamart.json
```

## Schema

```json
{
  "platform": "Blinkit",
  "total_stores": 2100,
  "total_cities": 253,
  "cities": {
    "New Delhi": [
      {"store_id": "34748", "pincode": "110001", "latitude": "28.6285", "longitude": "77.2205"},
      ...
    ],
    ...
  }
}
```

Cities are ordered by store count (largest first). Within a city, entries are sorted by pincode.

## Finding a store

Open the JSON on GitHub and use Ctrl+F / Cmd+F to search for your city.

---

Maintained by [Mindcase](https://github.com/mindcase-co).
