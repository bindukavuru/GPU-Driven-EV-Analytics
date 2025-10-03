# GPU-Driven Electric Vehicle Analytics 🚗⚡

A high-performance data analytics project built using RAPIDS cuDF, Dask, Python, CUDA, and Plotly. This project processes 250K+ electric vehicle records and showcases the speed advantage of GPU acceleration for ETL operations.

## 🔧 Tech Stack
- RAPIDS cuDF, Dask, CUDA
- Python, Pandas
- Plotly (for visualizations)
- Google Colab (T4 GPU)

## 🚀 Project Highlights
- Performed GPU-accelerated ETL operations (filtering, grouping, aggregation) on over 250,000 electric vehicle records.
- Reduced ETL runtime by **~85%**, achieving **~5.5x speedup** over traditional Pandas.
- Visualized top EV brands and the evolution of electric range across model years.

## 📊 Key Insights
- **Tesla** dominates BEV registrations in Washington State.
- Average electric range has significantly improved post-2016.
- Real-time filtering and GPU-based processing enables scalable EV policy modeling.

## 📈 Visualizations
- Top 10 EV Makes (Bar Chart)
- Avg. Electric Range by Year (Line Chart)

## 📌 Performance Benchmark
| Operation     | Runtime (Pandas) | Runtime (cuDF) | Speedup |
|---------------|------------------|----------------|---------|
| BEV Filter + Groupby | 0.0739 sec       | 0.0135 sec     | ~5.47x  |
