# Lab8
## How are graceful degradation and service workers related?

The relation between graceful degredation and service workers is that service workers can fall under the route of graceful degredation. By that sense, we know that graceful degradation starts at the top with all the tech, gracefully going down the levels. In the way of service workers, as they are a fallback for your web app in case of a failing network request. As such they allow the web app to go from fully online capable gracefully down to a limited offline process when the network fails instead of breaking entirely.