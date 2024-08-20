## About Chirper [WIP]

I might change that name later, but this is essentially Laravel's "Hello World" example that I'm planing on heavily modifying.

## How to Build and Run Locally

Once you clone or download the repository make sure you're in the project root.
Then bring up the Docker containers with Sail:
```shell
./vendor/bin/sail up -d
```

Then run the migrations:
```shell
./vendor/bin/sail artisan migrate
```

Then bring up Vite to build the front end:
```shell
./vendor/bin/sail npm run dev
```
