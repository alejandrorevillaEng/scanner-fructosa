# scanner-fructosa
Fructose Scanner es una web app pensada para personas con intolerancia a la fructosa. Permite escanear el código de barras de un producto o buscar un alimento por nombre y ver, de forma clara y rápida, un semáforo de riesgo (🟢 seguro / 🟡 precaución / 🔴 no recomendado) basado en el contenido estimado de fructosa y otros azúcares relacionados.

El proyecto usa un backend en Java con Spring Boot que consulta dos fuentes de datos abiertas:

Open Food Facts: para productos envasados (códigos de barras), obteniendo ingredientes y azúcares.

USDA FoodData Central: para alimentos genéricos (fruta, verdura, básicos), obteniendo valores de fructosa, glucosa y otros nutrientes.

La lógica de semáforo se aplica en el backend y los resultados se muestran en una interfaz web sencilla y responsive.

![Java](https://img.shields.io/badge/Java-21-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Open Food Facts](https://img.shields.io/badge/Open_Food_Facts-API-008751?style=for-the-badge&logo=openfoodfacts&logoColor=white)
![USDA FoodData](https://img.shields.io/badge/USDA_FoodData_Central-API-003D7C?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgZmlsbD0id2hpdGUiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZD0iTTggMGE4IDggMCAxIDAgMCAxNkE4IDggMCAxIDAgOCAwbTAgM2E1IDUgMCAxIDEtLjAwMSA5Ljk5OUE1IDUgMCAwIDEgOCAzem0tMiA1YTIgMiAwIDEgMCAwIDQgMiAyIDAgMCAwIDAtNHptNCAwYTQgNCAwIDEgMS0uMDAyIDcuOTk4QTQgNCAwIDAgMSAxMCA4eiIvPjwvc3ZnPg==&logoColor=white)
