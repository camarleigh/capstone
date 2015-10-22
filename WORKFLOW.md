

HomeView
  enter @
  enter going
  click of go  triggers event:              HomeView -> RouteView
    query Google Maps API
      return 3 routes
    loop through those 3 routes,
      using lon & lat for all pts along the route
        sum the elevation changes
        avg the elevation changes
        return routes in order from least to most elevation changes
        assign to values[heels(0), flats(1), sneakers(2)]
        return values[heels(0), flats(1), sneakers(2)]
RouteView
  display radio button choices of routes
  click of one radio button triggers event:  RouteView -> MapView
    return n (one route)

MapView
  display n
  refresh n @ suggested refresh rate
  click of finish button triggers event:      MapView -> FinisView

FinisView
  click of new route button triggers event:   FinisView -> HomeView 
