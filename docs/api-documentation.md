# API Documentation

## POST

/webhook/dental-appointment

### Request

```json
{
  "name":"Vinay Kumar",
  "email":"abc@gmail.com",
  "phone":"9891648446",
  "treatment":"General Checkup",
  "preferredDate":"2026-07-20",
  "notes":"Tooth Pain"
}
```

### Response

```json
{
  "success":true,
  "message":"Appointment enquiry submitted successfully."
}
```