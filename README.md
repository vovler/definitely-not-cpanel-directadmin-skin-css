# Definitely-not-cPanel DirectAdmin skin/custom-css

**Version: 2.0**

It's sad that cPanel increased prices so much, especially for people that run a $5 VPS or sell shared hosting for low cost. There were price increases of about 1000% for some of their clients in 2019. Roughtly a year later, they announced price increases again for Jan 2021, similarly as bad.<br>
Some moved to Plesk cause it's effectively cheaper than cPanel, the only issue is that Plesk is owned by the same parent company as cPanel.<br><br>
Many made the move to DirectAdmin, however it is not as polished, and some features feel clunky. And for those used to cPanel's paper_latern skin, DirectAdmin's skins are a bit off-putting.<br>
Since I don't think DirectAdmin will make a skin 100% equal to cPanel for PR reasons, I decided to customize their Evolution skin to resemble cPanel's.<br><br>

## How does it look:

### Before:
![Before](https://i.imgur.com/ozzUha4.png)
### After (including some menu organization changes):
![After](https://i.imgur.com/Gl5fMl6.png)

## How to install:
1) In DirectAdmin's admin settings, inside "Skin Manager", change the skin to Evolution
2) Using your favorite FTP/STFP program, go to "/usr/local/directadmin/data/skins/evolution/assets/"
3) Upload the css file and optionally the icons file  (dont forget to clear cache if you upload the icons).
4) In DA's admin settings go to "Customize Evolution Skin"
5) At "External CSS URL" write "/assets/custom.css" and submit.
6) Optionally, change the logo to a logo with white background.
7) Optionally, in DA's admin settings, inside "Customize Evolution Skin" organize the Menu:User / Reseller / Admin to resemble cPanel's. 
8) Optionally, remove all unecessary widgets except "WGT_USER/RESELLER/ADMIN_STATS" for a cleaner look in the right widget bar.

## F.A.Q.:
**Q)** Is this mobile responsive?<br>
**A)** Yes

**Q)** Have you tested this in the reseller and admin panel?<br>
**A)** Mostly not, 99% of the attention was spent at the regular user panel, including changing the color of user icons. Icons that are not displayed at the user panel have not been looked at, only color edited in bulk.

**Q)** Will you ever improve the reseller or admin panel look?<br>
**A)** Eventually™. But you can fork this, improve it yourself and create a pull request.

**Q)** The widget bar lost some of it functionality, is it intended?<br>
**A)** Yes. You can remove some of the display:none's to restore the funtionality that you want.

**Q)** Ewww. Your css code looks terrible.<br>
**A)** Yes.
