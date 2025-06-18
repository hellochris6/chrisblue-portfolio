#### Currently Working On
Developing a complete asset management workflow integrating Iconik with Airtable. The process includes:

- A Python script that fetches assets from Iconik filtered by specific criteria (e.g., unknown media type, archived status).
- Uploading detailed asset records into Airtable in batches.
- An Airtable automation script that integrates with the Iconik API to update asset metadata.
- Extracting file extension info from Airtable records, mapping it to the correct MIME type.
- Sending authenticated PUT requests to Iconik to update the asset’s media type and related metadata.
- Implementing error handling and updating Airtable confirmation fields upon successful completion.
- Ensuring accurate and up-to-date media classifications for assets.