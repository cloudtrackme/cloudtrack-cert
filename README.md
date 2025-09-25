# CloudTrack Certificate (CRC)

CloudTrack Certificate (CRC) is an **open standard** for proving authorship and authenticity of music releases.  
It defines a JSON schema for release certificates and provides tools for verifying them.

## 📦 Features
- JSON schema for CloudTrack Release Certificates
- Public key for signature verification
- CLI / API examples to verify certificates
- Open for adoption by any platform

## 🔍 Example Certificate
```json
{
  "certId": "3baed3b1-62d2-4f7b-8700-17e20be6c300",
  "issuer": "CloudTrack",
  "status": "valid",
  "track": {
    "title": "Coding Atmosphere",
    "userId": 43,
    "uuid": "e1bc84b9-ec35-45b2-8a00-a24c78eb9641"
  },
  "hash": {
    "mp3_sha256": "6e98710e...",
    "wav_sha256": "1c6e8eb1..."
  },
  "timestamps": {
    "issuedAt": "2025-09-25T16:55:37Z"
  },
  "verify": {
    "url": "https://cloudtrack.me/verify/3baed3b1-62d2-4f7b-8700-17e20be6c300"
  }
}
