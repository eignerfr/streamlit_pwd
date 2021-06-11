# Content of Procfile
# old: web: streamlit run --server.enableCORS false --server.port $PORT app.py
web: sleep 10 && touch '/tmp/app-initialized' & bin/start-nginx streamlit run --server.enableCORS false --server.port 8501 app.py

