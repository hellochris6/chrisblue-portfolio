#### Currently Working On
**Situation:** Identify Iconik assets missing media type classification (UNKNOWN) and programmatically correct them by adding the appropriate component metadata based on file extension.

**Task:** Develop and refine an API-based filter for listing archived and unknown media assets in Iconik; fetch list and update component information for each asset (media type and metadata).

**Actions:**
- Built a FastAPI app with endpoints to start the ljob and check status	
- Wrote a background task runner that: 
- Queries Iconik for assets with media_type='UNKNOWN' and is_archived=true		
- Infers type from file extension
- Posts new components to Iconik with appropriate metadata
- Deployed the app live using Render
- Added progress tracking via in-memory job status store

