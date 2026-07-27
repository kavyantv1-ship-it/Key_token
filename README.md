# 🔐 GRW KEY SYSTEM

## License Key Management System

### Admin Commands

#### To Enable/Disable a Key
1. Open `keys.json`
2. Find the key
3. Change `"active": true` or `"active": false`

#### To Revoke a Key
1. Open `keys.json`
2. Find the key
3. Change `"device_id": "REVOKED"`

#### To Force Shutdown All Tools
1. Open `shutdown.txt`
2. Change to `true`
3. All tools will close immediately

#### To Reset Daily Usage
1. Open `keys.json`
2. Find the key
3. Set `"used_today": 0`
4. Update `"last_used": "YYYY-MM-DD"`

---

## Key Format