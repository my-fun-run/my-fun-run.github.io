## REST Endpoints

* `/user`

    * `GET`
    
        * Request: (none)
        * Response: 
            * Body: `User[]`       
        
* `/user/{id}`

    * `GET`
    
        * Request
            * Path: 
                `id`: `long`
                
        * Response:
            * Body: `User`
     
* `/user/{id}`      

    * `PUT`  
    
        * Request
             * Path: 
                 `id`: `long`
                                   
        * Response:
             * Body: `User`
             
* `/user/{id}`      

    * `DELETE`  
    
        * Request
             * Path: 
                 `id`: `long`
                                   
        * Response:
             * Body: `User`    
             
* `/event`

    * `GET`
    
        * Request: (none)
        * Response: 
            * Body: `Event[]`       
        
* `/event/{id}`

    * `GET`
    
        * Request
            * Path: 
                `id`: `long`
                
        * Response:
            * Body: `Event`
     
* `/event/{id}`      

    * `PUT`  
    
        * Request
             * Path: 
                 `id`: `long`
                                   
        * Response:
             * Body: `Event`

* `/event`      

    * `POST`  
    
        * Request
             * Path: 
                 `id`: `long`
                                   
        * Response:
             * Body: `Event`
                          
* `/event/{id}`      

    * `DELETE`  
    
        * Request
             * Path: 
                 `id`: `long`
                                   
        * Response:
             * Body: `Event`             
                      
* `/history`

    * `GET`
    
        * Request: (none)
        * Response: 
            * Body: `History[]`       
        
* `/history/{id}`

    * `GET`
    
        * Request
            * Path: 
                `id`: `long`
                
        * Response:
            * Body: `History`
            
* `/history`

    * `POST`
    
        * Request
            * Path: 
                `id`: `long`
                
        * Response:
            * Body: `History`
                 
* `/history/{id}`      

    * `PUT`  
    
        * Request
             * Path: 
                 `id`: `long`
                                   
        * Response:
             * Body: `History`
             
* `/history/{id}`      

    * `DELETE`  
    
        * Request
             * Path: 
                 `id`: `long`
                                   
        * Response:
             * Body: `History`             

* `/comment`

    * `GET`
    
        * Request: (none)
        * Response: 
            * Body: `Comment[]`       
        
* `/comment/{id}`

    * `GET`
    
        * Request
            * Path: 
                `id`: `long`
                
        * Response:
            * Body: `Comment`
            
* `/comment`

    * `POST`
    
        * Request
            * Path: 
                `id`: `long`
                
        * Response:
            * Body: `Comment`
                 
* `/comment/{id}`      

    * `PUT`  
    
        * Request
             * Path: 
                 `id`: `long`
                                   
        * Response:
             * Body: `Comment`
             
* `/comment/{id}`      

    * `DELETE`  
    
        * Request
             * Path: 
                 `id`: `long`
                                   
        * Response:
             * Body: `Comment`             
                                 