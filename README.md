# Project Initialization & planification

This project is about developing a personal Portfolio, to further enhance my Web Dev abilities, expand my brand and have something to show of my personal projects and private ones in a professional way.

<details>
    <summary> Expand to see the project overview diagram</summary>
    <picture>
        <img src="" alt="Image of the Overview"/>
    </picture>
</details>

## Database initialization and development

The project leverages the power of supabase, a powerfull cloud Postgres manager, we don't have to develop the whole infrastructure and we can focus on what's really important without having to worry about docker, kubernetes or any infraestructure necessary to deploy our main DB.

<details>
    <summary> Database E/R diagram </summary>
    <picture>
        <img src="./docs/PortfolioDB.png" alt="Database infraestructure"/>
    </picture>
</details>

<details>
    <summary> Supabase final diagram </summary>
    <picture>
        <img src="./docs/Schema1.png" alt="Supabase screencapture 1"/>
    </picture>
    <picture>
        <img src="./docs/Schema2.png" alt="Supabase screencapture 2"/>
    </picture>
</details>

> The main objective of this DB architecture is to simplify the data enough to make little queries to render the data recursively and conditionally.

## Main Services Architecture

![Main services architecture]()

### Routes

I'm going to define the main routes for both Web & API endpoints.

#### Web Routes

* / - Will be the main entrypoint of the Web page.
* /blog - Will be the entrypoint for the blog page.
* /contact - Will be the entrypoint for the contact page.

#### API Endpoints

#### Go API Endpoints

* /api - Will be the main entrypoint of the application.
  * /api/image - Will be the main entrypoint for the image processing part of the application.
