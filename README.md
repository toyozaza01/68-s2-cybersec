# Cyber Security

## Information
* ###### Prapatsorn Chaiprom
* 6702041510041
* s6702041510041@email.kmutnb.ac.th

## Enironment
```sh
cp env.simple .env
```

## Running Service
### Database
```sh
docker compose -f db.yaml up #Monitoring
docker compose -f db.yaml up -d #BackgroundRun
```

### Admin
```sh
docker compose -f admin.yaml up #Monitoring
docker compose -f admin.yaml up -d #BackgroundRun
```

### APP
```sh
docker compose -f app.yaml up #Monitoring
docker compose -f app.yaml up -d #BackgroundRun
```
