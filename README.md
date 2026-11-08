# Drink Planner & Recipe Generator

Household bar inventory and AI drink recipes. Separate codebase and Supabase project from [Pantry Meal Planner](https://github.com/jnuber/pantry-meal-planner).

## Setup

1. Create a new Supabase project (do not reuse the kitchen database).
2. Run `supabase_schema.sql` in the SQL editor.
3. Copy `.streamlit/secrets.toml` locally (never commit it):

```toml
GEMINI_API_KEY = "..."
SUPABASE_URL = "..."
SUPABASE_KEY = "..."
```

4. `python -m venv venv && source venv/bin/activate && pip install -r requirements.txt`
5. `streamlit run app.py` or `./run.sh`

Version: **1.1.3**
