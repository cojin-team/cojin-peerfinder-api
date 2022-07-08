* **URL**

  /admin/allPeers

* **Method:**
  
  `POST`

* **Data Params**

  { "auth": "adminPassword" }

* **Success Response:**

  * **Code:** 200 <br />
  * **Content:** `[peers(str)]`
 
* **Error Response:**

  * **Code:** 403 FORBIDDEN <br />
    **Content:** `Forbidden` <br />
    **Cause:** The admin password is not valid
