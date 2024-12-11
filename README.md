# Test Notes and Observations

## APIs Tested
During the testing process, several APIs were evaluated, including:
- **CoinGecko**
- **Moralis**
- **BscScan**
- **Mobula**

### Summary
Mobula stood out as the most comprehensible and user-friendly API for my needs. 
But then I realised the way to achieve this test is to use public rpc nodes !

---

## Bugs Identified in Mobula API

### 1. **Page Loading Performance**
- **Issue**: Pages are slow to load.

### 2. **Market History Endpoint Issues**
- **Endpoint**: [Market History API](https://docs.mobula.io/rest-api-reference/endpoint/market-history)
- **Description**: The page occasionally crashes under the following conditions:
  - When searching for Bitcoin and clicking "Send."
  - When selecting the `1h` time interval.

### 3. **Admin Dashboard Issues**
- **URL**: [Mobula Admin Panel](https://admin.mobula.fi/admin/default)
- **Description**: 
  - Discord and Telegram logos are not displaying correctly (KO).

### 4. **Free API abuse**
- **Issue**: I've been able to acquire a free api key with just a temporary mail, maybe reinforce security in order to not have the free api abused.