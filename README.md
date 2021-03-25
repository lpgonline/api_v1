# api_v1
API_V1 instructions

<br />
Based on Project JSON-Server:  
https://github.com/typicode/json-server
<br />
<br />

<b>Docker usage:</b>
```
docker container run -d -p 80:3000 lpgonline/lp_images:api_v1 npm start --prefix /api
```

Podman Get Data:  
GET http://localhost/cars    
All records from local database will be displayed.  
![image](https://user-images.githubusercontent.com/32129972/112537372-59b6f600-8d8d-11eb-9fda-096123724bca.png)

Podman Post Data  
POST http://localhost/cars  
JSON Like:  
```
{  
    "Cor": "preto",  
    "Placa": "ddd-4444",  
    "Ano": "2018",  
    "Modelo": "eee"  
}
```

![image](https://user-images.githubusercontent.com/32129972/112538256-730c7200-8d8e-11eb-91e4-edd4ffc63c12.png)



Web Browser access:  
http://localhost/cars  
All records from local database will be displayed.  

![image](https://user-images.githubusercontent.com/32129972/112536497-4fe0c300-8d8c-11eb-9b05-3c535471b503.png)

To view a especific record, you can search by ID - localhost/cars/[1,2,3...]  
http://localhost/cars/1  

![image](https://user-images.githubusercontent.com/32129972/112536765-a1894d80-8d8c-11eb-8a1d-32fc5a3cd1b3.png)
