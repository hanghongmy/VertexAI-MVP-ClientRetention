# 🎯 Vertex AI MVP - Client Retention

curl -X POST \
  -H "Authorization: Bearer $(gcloud auth print-access-token)" \
  -H "Content-Type: application/json" \
  -d @sample_request.json \
  "https://us-central1-aiplatform.googleapis.com/v1/projects/ethereal-reef-451601-v0/locations/us-central1/endpoints/6155287094127230976:predict"

