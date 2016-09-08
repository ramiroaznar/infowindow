# How to add an infowindow to a CARTO dashboard

```javascript
    myapp.layers[1].infowindow.update({
      fields: [
        {
          "name": "name",
          "title": true
        },
        {
          "name": "pop2005",
          "title": true
        }
      ]
    })
```

