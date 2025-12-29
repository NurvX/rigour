# Get MaxMind License Key

For GeoIP and ASN lookups, Rigour uses the MaxMind service. This service is completely free to use, but requires a license key. To obtain a MaxMind license key, follow these steps:

1. **Create a MaxMind Account**:
   - Setup a free account on the MaxMind website: [https://www.maxmind.com/en/geolite2/signup](https://www.maxmind.com/en/geolite2/signup).

2. **Generate a License Key**:
    - After logging into your MaxMind account, navigate to the "Manage License Keys" section.
    - Click on "Create a New License Key".
    - Provide a name for the key (e.g., "Rigour")
    - Click Confirm to generate the key.

3. **Record the License Key & Account ID**:
    - Copy your Account ID and store it in your .env file as `MAXMIND_ACCOUNT_ID=your_account_id_here`.
    - Copy the generated license key and store it in your .env file as `MAXMIND_LICENSE_KEY=your_license_key_here`.
