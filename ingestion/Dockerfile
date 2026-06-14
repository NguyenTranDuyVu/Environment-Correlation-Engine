FROM python:3.11-slim

ENV PYTHONUNBUFFERED=1 \
    PYTHONDONTWRITEBYTECODE=1

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY common_lib/ ./common_lib/
COPY sources/ ./sources/

# Entry point will be specified by execution command (e.g. python -m sources.api_a.main)
CMD ["python"]
