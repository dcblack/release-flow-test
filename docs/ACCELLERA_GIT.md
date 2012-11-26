## Information on GITHUB setup for Accellera.org groups

### General idea

In order to accomplish this, we have:

a. Setup accounts on accellera.org, hostingmail.earthlink.net, and github.com.
b. Accounts are setup for each GRP, where GRP is one of {lwg, vwg, tlm, or cci}.

This results in updates from GitHub resulting in the following chain of events:

1. GitHub posts message to GRP_git@accellera.org
2. GRP_git@accellera.org forwards message to GRP@lists.accellera.org
3. GRP@lists.accellera.org reflects to all distribution group members
4. GRP_git@accellera.org ignores resent-from lists.accellera.org messages

### Steps to setup repository notifications

1. Obtain an accellera.org e-mail account
   - E-mail to current coordinator [lynn@accellera.org](mailto:lynn@accellera.org)
   - Record the *GROUP* e-mail address (typically *GROUP*_git@accellera.org) and password
2. Create a github account corresponding to the e-mail account
   - Go to [GitHub](http://www.github.com)
   - Sign-out if necessary (click door icon at upper-right)
   - Click **Sign up for free**
   - Enter *Username* **GROUPgit**
   - Email address from step 1
   - Enter *Password* **acce1gitGROUP**
3. Add the github account to the **Observer** team
   - If not a team manager, then request from [David Black](dcblack@mac.com)
4. Subscribe the github account to the *GROUP* e-mail list (e.g. lwg@accellera.org)
5. Add a mail filter under Preferences
   - [Mail login](https://hostingmail.earthlink.net/ajax_login/login.php)
   - Click **PREFERENCES** tab
   - Click **Filtering Preferences**
   - Click **New Message Rule**
   - Change the *Rule Name* to 
   - Set **From** **Equal to** **notifications@github.com**
   - Set **Subject** **Contains** **[repository-name]**
   - Action **FORWARD** *GROUP*@accellera.org
   - Click **SAVE**
   - Click **Sign Out** (Upper-Right corner)

### To do:

- Organization independent e-mails for administrators and managers

### Current data

 Group | Email_address         | Email_PW    | Git_Id | Git_PW      | State
 :---: | --------------------- | ----------- | ------ | ----------- | -----
  lwg  | lwg_git@accellera.org | see below   | lwggit | see below   | testing
  vwg  | vwg_git@accellera.org | see below   | vwggit | see below   |     
  tlm  | tlm_git@accellera.org | see below   | tlmgit | see below   |     
  cci  | cci_git@accellera.org | see below   | ccigit | see below   |     


**Do <span style="color:red">not</span> modify the following block**  
Request [me](mailto:dcblack@mac.com) for the password to the following if you need access.

```
-----BEGIN PGP MESSAGE-----
Version: 10.2.1.4461

qANQR1DDDQQJAwIIf0eb8inevb/SpwGuicKiuw0kfzSUOn1l0RokTjDAmAYaQNH1
UkI947b8yG0VSPdbqh1Ui/UEWKTUGK3hl8VvDkfvpv/YbPygaUjxajAhl8QZujtX
xPSD8ayzazRC2Im5FUhsXQGAMHG/ckLcWDabIXZ66MtWAh1hRWHALtv3ZCHl7sO8
cJ61qAkICwcQBMByVvLPpiDWXIwdM7w13vq6aT/Pc8IZoBz07EyJ9HVpQhXz
=xTkP
-----END PGP MESSAGE-----
```

## The end