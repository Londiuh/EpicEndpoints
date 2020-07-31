# Creative favorites
Returns a JSON containing your favorited creative islands

## Request
| Method | Auth | URL |
| - | - | - |
| `GET` | `token` | https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/creative/favorites/{account_user} |

Replace {account_user} with the token owner account ID

### Parameters (optional)
- limit = `int`

## Example
`https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/creative/favorites/2d4b570fab8f4d1e9510998f4253962c?limit=3`

## Utility
Useful to get all favorite creative islands (because fortnite only gives you 30)
