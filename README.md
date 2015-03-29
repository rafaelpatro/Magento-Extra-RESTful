# Extra RESTful

Developers are invited to include this reusable extension in their projects for better connectivity.
Extra RESTful is permissively licensed for this reason.
Suggestions for more resources to support are welcome,
just raise an [issue](https://github.com/clockworkgeek/Magento-Extra-RESTful/issues).

### New Attributes

- **Catalog Product / Read / Created At** (`created_at`)
- **Catalog Product / Read / Updated At** (`updated_at`)
- **Catalog Product / Read / Has Options** (`has_options`)
- **Catalog Product / Read / Has Required Options** (`required_options`)
- **Customer / Read / Updated At** (`updated_at`)

### New Resources

- **Catalog / Category / Retrieve**
  - `GET /api/rest/categories`
  - `GET /api/rest/categories/store/:store`
  - `GET /api/rest/categories/:id`
  - `GET /api/rest/categories/:id/store/:store`