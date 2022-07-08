* **URL**

  /postpeer

* **Method:**

  `POST`

* **Data Params**

  `{ peer: 'ip:port' }`

* **Success Response:**
  
  <_What should the status code be on success and is there any returned data? This is useful when people need to to know what their callbacks should expect!_>

  * **Code:** 200 <br />
  * **Content:** `OK`
 
* **Error Response:**

  * **Code:** 500 <br />
    **Content:** `Invalid JSON format`<br />
    **Raised when:** JSON payload doesn't have a peer address
