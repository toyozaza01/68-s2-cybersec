# Cyber Security

## Information
* ###### Prapatsorn Chaiprom
* 6702041510041
* s6702041510041@email.kmutnb.ac.th

## Enironment
```sh
cp env.simple .env
```

## Runnuing Service

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