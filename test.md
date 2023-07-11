#TEST
##Test
###Test

'''javascript
const A = () =>{
	return (
		<demoContext.Consumer>
			{
				data => <h1>{data}</h1>
			}
		<demoContext.Consumer>
	)
}