excel:
  file_path: input.xlsx
  sheet_index: 0
  payload_column_index: 1

api:
  endpoint_1: https://api.endpoint1.com/test
  endpoint_2: https://api.endpoint2.com/test
  timeout: 30
  headers:
    Content-Type: application/json

execution:
  max_workers: 5

comparison:
  ignore_fields:
    - timestamp
    - requestId
    - meta.generatedAt

report:
  output_dir: reports
