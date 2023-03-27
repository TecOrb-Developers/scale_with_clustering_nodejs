# scale_with_clustering_nodejs


Direact link to main website (https://nodejs.org/api/cluster.html)


What is clustering?
Clusters of Node.js processes can be used to run multiple instances of Node.js that can distribute workloads among their application threads.
When process isolation is not needed, use the worker_threads module instead, which allows running multiple application threads within a single Node.js instance.

What we have implemented in this project?
- Use cluster
- Number of cluster
- cluster Listing in os


#Required dependencies:
- Node is installed (v 14.x)
- Postman is installed (Version 10.12.3-230318-0431)
- Git is installed.


### Server 
- PORT=4000
- HOST=localhost


### Major steps are followed to create/setup:
`npm install`



### Run local server
`npm start`


### Run cluster 
`npm cluster`


# postman  api url
type get  "{host-url}/api/intense"

