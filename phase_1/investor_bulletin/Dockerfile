FROM python:3.11.4

# WORKDIR /app

COPY . .

WORKDIR phase_1/investor_bulletin

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8000

CMD ["fastapi", "run", "api/main.py", "--port", "8000"]
