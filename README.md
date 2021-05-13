# Tours-useEffect

Create basic React app - Tours.

Example of using:

- useEffect - to fetch data from api, using fetch(). After fetch() have to convert to json-format.
- conditional rendering - {readMore ? <A /> : <B />}
- toggle button - we can Read More or Show Less
  - `<button onClick={() => setReadMore(!readMore)}> {readMore ? 'Show Less' : 'Read More'} </button>`
- deleteTour - filter array to remove tour by id
  - `const removeTour = id => { const newTours = tours.filter(tour => tour.id !== id) setTours(newTours) }`
