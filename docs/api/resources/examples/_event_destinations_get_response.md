
#### Example Response

```json
{
  "id": "ed_2EmMPinOUIowjK69EWlUOvNkTyc",
  "metadata": "{\"environment\":\"dev\", \"stream\":1}",
  "created_at": "2022-09-14T22:58:03Z",
  "description": "kinesis dev stream 1 of 3",
  "format": "json",
  "target": {
    "firehose": null,
    "kinesis": {
      "auth": {
        "role": {
          "role_arn": "arn:aws:iam::123456789012:role/example"
        },
        "creds": null
      },
      "stream_arn": "arn:ngrok-local:kinesis:us-east-2:123456789012:stream/mystream2"
    },
    "cloudwatch_logs": null
  },
  "uri": "https://api.ngrok.com/event_destinations/ed_2EmMPinOUIowjK69EWlUOvNkTyc"
}