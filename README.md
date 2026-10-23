# GDP Data Dashboard — Streamlit / Pandas Example

This repository contains a **Streamlit GDP dashboard template/example**. It loads local CSV GDP data with Pandas, reshapes yearly columns, filters countries and years, and renders interactive charts and metrics.

**中文**：基于 Streamlit / Pandas 的 GDP 数据展示示例，用于学习 CSV 数据清洗、筛选与可视化。属于模板性质项目，不代表独立开发了数据平台或完成生产环境部署。

## Primary portfolio focus

For my Python automation and QA work, see the [Python Automation Portfolio](https://github.com/xiaowang1688/python-automation-starter/blob/main/PORTFOLIO.md), especially the runnable [API monitoring project](https://github.com/xiaowang1688/python-automation-starter) and [security automation example](https://github.com/xiaowang1688/smart-contract-vulnerability-scanner).

## Run locally

```bash
python -m pip install -r requirements.txt
streamlit run streamlit_app.py
```

The dashboard reads [`data/gdp_data.csv`](data/gdp_data.csv) and uses a historical period ending in **2022**. Some data points are missing; the contents are not a live GDP feed.

## Code

- [`streamlit_app.py`](streamlit_app.py) — Streamlit UI, Pandas reshape/filter logic
- [`requirements.txt`](requirements.txt) — Streamlit and Pandas dependencies

## Credits and scope

Adapted from the Streamlit GDP dashboard template/example. See [Streamlit](https://streamlit.io/) for the original framework and examples. This is a learning/demo project, not a production analytics service.
