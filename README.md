 # Ecommerce-Website
Ecommerce web application using Angular9 | Node.js | Express.js | MongoDB   (MEAN Stack)

## Objective
* The goal is to build a Ecommerce web application where users can buy and sell products online.
* This app contains 2 pannels for admin and for user.Admin can add Products with images and can add Users. Users can add item in cart and can place the order.    

## System Design
### Architecture
* Web Application uses a Client-Server Architecture with:
  * Client components developed using Angular 9 - Folder - '/frontend'   
  * Server Restful Api's developed using Node.js, Express.js, MongoDB - Folder - '/backend'

<table>
<thead>
<tr>
<th>Area</th>
<th>Technology</th>
</tr>
</thead>
<tbody>
	<tr>
		<td>Front-End</td>
		<td>Angular, Bootstrap, HTML5, CSS, Typescript</td>
	</tr>
	<tr>
		<td>Back-End</td>
		<td>Express, Node.js</td>
	</tr>
  <tr>
		<td>Authentication</td>
		<td>JWT(JSON Web Tokens)</td>
	</tr>
	<tr>
		<td>API Testing</td>
		<td>Postman</td>
	</tr>
	<tr>
		<td>Database</td>
		<td>MongoDB</td>
	</tr>
</tbody>
</table>

## Steps for Project Execution :

##### Client Install
```
cd frontend
npm install
ng serve 
```
##### Server Install
```
cd backend
npm install
node server.js
```

## Screenshots

#### LoginPage
![](https://user-images.githubusercontent.com/55733010/93338287-cf269480-f847-11ea-86d1-2f89ab0b2c93.png)

#### User HomePage
![](https://user-images.githubusercontent.com/55733010/93338432-f3827100-f847-11ea-91de-63c836dc27cf.png)

#### Add to Cart Section(Only for Users)
![](https://user-images.githubusercontent.com/55733010/93338539-144ac680-f848-11ea-9704-0e3b5987eb1f.png)

#### Track Orders Section(Only for Users)
![](https://user-images.githubusercontent.com/55733010/93338665-3a706680-f848-11ea-9cdb-6f4041e3aa01.png)

#### Checkout & Payment
![](https://user-images.githubusercontent.com/55733010/93338953-a05cee00-f848-11ea-8e6f-12cd5d95ff00.png)

#### Admin HomePage
![](https://user-images.githubusercontent.com/55733010/93339171-e1ed9900-f848-11ea-93c0-9fdfc9be12c5.png)

#### Admin DashBoard(New Product)
![](https://user-images.githubusercontent.com/55733010/93339282-03e71b80-f849-11ea-8345-a1bb9c4d50c9.png)

#### Admin DashBoard(New User)
![](https://user-images.githubusercontent.com/55733010/93339430-34c75080-f849-11ea-9ef1-0ae2799058dd.png)
