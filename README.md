# awsproject
# Chatbot using AWS Lex
{
  "alternativeIntents": [
    {
      "intentName": "AMAZON.FallbackIntent",
      "nluIntentConfidence": null,
      "slots": {}
    }
  ],
  "botVersion": "$LATEST",
  "dialogState": "ElicitIntent",
  "intentName": "BookCab",
  "message": "Thankyou for booking a cab. Have a safe journey and enjoy your ride to main street!",
  "messageFormat": "PlainText",
  "responseCard": {
    "contentType": "application/vnd.amazonaws.card.generic",
    "genericAttachments": [
      {
        "attachmentLinkUrl": null,
        "buttons": [
          {
            "text": "Book Return Trip?",
            "value": "Book a Cab"
          },
          {
            "text": "No",
            "value": "No"
          }
        ],
        "imageUrl": null,
        "subTitle": "Booking Information",
        "title": "Booking Information"
      }
    ],
    "version": "1"
  },
  "sentimentResponse": {
    "sentimentLabel": "MIXED",
    "sentimentScore": "{Positive: 0.26016685,Negative: 0.021052489,Neutral: 0.33579963,Mixed: 0.38298094}"
  },
  "sessionAttributes": {},
  "sessionId": "2023-01-14T09:26:14.615Z-WVmHfCEy",
  "slotToElicit": null,
  "slots": null
}
