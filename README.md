Microservice Auth Travel Online Application

Anggota Tim Developer:
* Denny Muharrom Ariawan
* Okky Septian

Proyek ini merupakan bentuk Aplikasi Travel Online yang terdiri dari 3 microservices :
1. Service Auth
2. Service Passenger
3. Service Transaction

Berikut merupakan Entity Relationship Diagram untuk proyek ini:
![alt text](https://github.com/Training-Java-Alterra-Team5/erd/blob/master/Travel%20Online%20Application.png)

Penjelasan ERD
1. Entitas
- User
- Role
- Bus
- Schedule
2. Hubungan antar entitas
- 1 User bisa memiliki banyak bus
- 1 User hanya bisa memiliki 1 Schedule
- 1 User hanya bisa memiliki 1 Schedule
- 1 Bus bisa memiliki banyak transaction
- 1 Bus hanya bisa memiliki 1 Schedule
- 1 Schedule bisa memiliki banyak transaction
