# Metabase Docker

Create a Metabase app using Docker and compose.

## Installation

Use the docker [compose](https://www.metabase.com/docs/latest/installation-and-operation/running-metabase-on-docker) to deploy.

```bash
#Create your DB user and password
echo "yourDBpassword" > .db_password
echo "yourDBuser" > .db_user
# Copy and Edit your environment variables
cp .env.example .env
vim .env
# Create App
docker compose up -d
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
