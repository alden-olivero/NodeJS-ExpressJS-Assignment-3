## Installation


1. **Install dependencies:**

  

   ```bash
   npm install express mongoose nanoid@3 dotenv

   ```


2. **Run the application:**

   Start the server using the following command:

   ```bash
   npm start
   ```

   

## API Endpoints

### Create Short URL

- **POST** `/api/v1/urls`
  
  **Request Body:**
  
  ```json
  {
    "originalUrl": "https://www.example.com"
  }
  ```
### Get All URL Details

- **GET** `/api/v1/urls`

### Get URL by Short Code

- **GET** `/api/v1/urls/:shortUrlCode`

### Update URL

- **PUT** `/api/v1/urls/:shortUrlCode`
  


### Delete URL

- **DELETE** `/api/v1/urls/:shortUrlCode`

### Redirect

- **GET** `/api/v1/urls/redirect/:shortUrlCode`
