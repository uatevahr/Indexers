# Indexers

This Repo contains Cardigann YML indexer definitions for [Prowlarr](https://github.com/Prowlarr/Prowlarr).

For more information on the formatting of the YML Indexer Definition, please see [our wiki entry](https://wiki.servarr.com/en/prowlarr/cardigann-yml-definition)

For Prowlarr Indexer Requests; please see [our request site](https://requests.prowlarr.com/)

# Definition Versions

Versions require Prowlarr Cardigann C# modifications.
Prowlarr will fall back to a previous version if no YML exists for the current version.

## Active Versions

- V1 Indexers
  - Prowlarr Cardigann v1 are base level standard YML
  - No new indexers are to be added to v1 as of 2021-10-13
  - V2 updates for indexers existing as v1 will be backported to V1 where possible until V1 is depreciated
- V2 Indexers
  - Prowlarr Cardigann v2 include several changes such as
    - Regex removal for Size parsing
    - Multiple Download Selectors
    - Optional Selectors
    - Testlink Torrents
    - InfoHash links
    - AllowRawSearch property in caps
  - All new indexers shall be added to v2 as of 2021-10-13
  
## Depreciated Versions

- None
