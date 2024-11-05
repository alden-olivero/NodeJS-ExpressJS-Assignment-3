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
  ![](outputImages\2.png)

### Get All URL Details

- **GET** `/api/v1/urls`
![](outputImages\1.png)
### Get URL by Short Code

- **GET** `/api/v1/urls/:shortUrlCode`
![](outputImages\3.png)
### Update URL

- **PUT** `/api/v1/urls/:shortUrlCode`
  ![](outputImages\4.png)


### Delete URL

- **DELETE** `/api/v1/urls/:shortUrlCode`
![](outputImages\5.png)
### Redirect

- **GET** `/api/v1/urls/redirect/:shortUrlCode`
![](outputImages\6.png)
![](outputImages\7.png)