* **URL**

  /admin/deletePeers

* **Method:**
  
  `POST`

* **Data Params**

  **Delete some peers:** <br />
  { "auth": "adminPassword", "peers": [ "peers_to_delete" ] }
  <br /><br />
  **Wipe peers:** <br />
  Just don't add peers list<br>
  { "auth": "adminPassword" }

* **Success Response:**

  * **Code:** 200 <br />
  * **Content:** `OK`
 
* **Error Response:**

  * **Code:** 403 FORBIDDEN <br />
    **Content:** `Forbidden` <br />
    **Cause:** The admin password is not valid