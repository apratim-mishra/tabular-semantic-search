Building a modern search app for Amazon e-commerce products leveraging tabular semantic search and natural language queries.

<div align="center">
  <table>
    <tr>
      <td align="center"><b>🔍 Core Features</b></td>
      <td align="center"><b>🛠️ Tech Stack</b></td>
    </tr>
    <tr>
      <td>
        • Semantic search for tabular data<br/>
        • Natural language query processing<br/>
        • Multi-attribute vector indexing<br/>
        • RESTful API endpoints<br/>
        • Tabular semantic search vs. text-to-SQL<br/>
        • Interactive web interface
      </td>
      <td>
        • OpenAI LLMs<br/>
        • MongoDB Atlas Vector Search<br/>
        • Superlinked<br/>
        • FastAPI<br/>
        • LlamaIndex<br/>
        • Streamlit
      </td>
    </tr>
  </table>
</div>

Perfect for developers building search functionality in e-commerce or structured data applications.


Our recommendation for each article:

- Read the article.
- Run the Notebook and the code using the [INSTALL_AND_USAGE](INSTALL_AND_USAGE.md) docs.
- Go deeper into the code



## 🏗️ Project Structure

```text
.
├── data/                                          # Directory where dataset files and processed data will be downloaded.
├── superlinked_app/                               # Main application source code
├── tools/                                         # Utility scripts and helper tools
├── .env                                           # Environment variables for local development
├── .env.example                                   # Template for environment variables
├── 1_eda.ipynb                                    # Notebook for Exploratory Data Analysis for the Amazon dataset
├── 2_tabular_semantic_search_superlinked.ipynb    # Demo notebook for Superlinked tabular semantic search
├── 3_tabular_semantic_search_text_to_sql.ipynb    # Examples of text-to-SQL queries
├── Makefile                                       # Running commands shortcuts
├── pyproject.toml                                 # Python project dependencies and metadata
└── uv.lock                                        # Lock file for uv package manager
```

## 💾 Dataset

We will use the [ESCI-S: extended metadata for Amazon ESCI dataset](https://github.com/shuttie/esci-s?tab=readme-ov-file) dataset released under the Apache-2.0 license.

It is an e-commerce dataset on Amazon products. 

The full dataset references ~1.8M unique products. We will work with a sample of 4400 products to make everything lighter, but the code is compatible with the whole dataset.


