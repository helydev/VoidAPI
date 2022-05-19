We have made a new API that connects to our **HCF Core** for
all of the external plugin creators!

Have questions? Please feel free to join our [support discord](https://discord.gg/tpkFXMwCG7) and
open a support ticket!

## API Usage
We have added many events, and will continue to add more!
If you need a specific event, and the API does not have the event, please join our [support discord](https://discord.gg/tpkFXMwCG7)
and tell us what new events you need!

All of our currently available usages are listed below:
```Java
public int getPlayerBalance(UUID uuid)
public int setPlayerBalance(UUID uuid, int balance)
public int addPlayerBalance(UUID uuid, int balance)
public int subtractPlayerBalance(UUID uuid, int balance)
public int getPlayerLives(UUID uuid)
public int setPlayerLives(UUID uuid, int balance)
public int addPlayerLives(UUID uuid, int balance)
public int subtractPlayerLives(UUID uuid, int balance)
public int getKills(UUID uuid)
public void setKills(UUID uuid, int kills)
public void addKills(UUID uuid, int kills)
public int getDeaths(UUID uuid)
public void setDeaths(UUID uuid, int deaths)
public void addDeaths(UUID uuid, int kills)
public int getStreak(UUID uuid)
public void setStreak(UUID uuid, int streak)
public void addStreak(UUID uuid, int streak)
public void removeCredits(UUID uuid, int credits)
public void addCredits(UUID uuid, int credits)
public void setHighstreak(UUID uuid, int amounts)
public boolean isStaffMode(Player player)
public boolean isStaffBuild(Player player)
public boolean isStaffBoard(Player player)
public boolean isVanish(Player player)
public void giveStaffMode(Player player)
public void removeStaffMode(Player player)
public void giveVanish(Player player)
public void removeVanish(Player player)
```
