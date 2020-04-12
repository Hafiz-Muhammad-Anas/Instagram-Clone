# React-Instagram-Clone-2.0
A reactive Single-Page Instagram-Clone with some new features!! 

**No longer maintained. But it works**


# Requirements
1. [GraphicsMagick](http://www.graphicsmagick.org/) for Image-processing.

# Usage
1. Fork the repo and then clone it or download it.

2. First install all dependencies:
    ```bash
    # with npm
    npm install
    
    # or with yarn
    yarn
    ```

3. Open PHPMyAdmin, create a DB & import `db.sql` file.
4. Create a `.env` file and insert the following code. Replace values with yours!!

    ```javascript
    PORT=YOUR_PORT
    SESSION_SECRET_LETTER="anything-secret"
    MYSQL_HOST="host"
    MYSQL_USER="user"
    MYSQL_PASSWORD="password"
    MYSQL_DATABASE="db"
    MAIL="your-email-for-sending email-verification-link"
    MAIL_PASSWORD="password-for-email"
    GOOGLE_GEOLOCATION_KEY='google-geolocation-key'
    ADMIN_PASSWORD='password-for-admin'
    ```
    
5. For front-end layer of this app to get access to `env` variables defined in `.env` file, run
    ```bash
    yarn env
    ```

6. Start the server
    ```javascript
    npm start [OR] yarn start
    ```

7. Now run the app
    ```javacript
    localhost:[PORT] (PORT=defined in .env)
    ```
    
# Todo
- [x] More image filters
- [x] Search
- [x] Block members
- [x] Hashtag feature
- [x] Mention members
- [x] JSDoc & comments
- [x] Admin system
- [x] Show if member is online
- [x] Show all online members (whome you've followed)
- [x] Description with react-helmet for SEO
- [x] Some serious code refactoring
- [x] Crush some bugs
- [x] Remove jQuery
- [x] UI testing
- [ ] Folder restructuring
- [ ] Performance optimization (Code Splitting, Image Lazyload, etc.)
- [ ] Express routes testing
- [ ] Like comments
- [ ] Upgrade packages
- [ ] Story feature
- [ ] Show mutual likes, comments & shares


