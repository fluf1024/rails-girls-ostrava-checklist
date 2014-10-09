#Checklist pro instalaci - Rails Girls Ostrava 2014

1) Stáhnout [RailsInstaller](https://github.com/railsinstaller/railsinstaller-windows/releases/download/3.0.0-alpha.2/railsinstaller-3.0.0.exe) a spustit ho.

2) Otevřít ```Command Prompt with Ruby on Rails``` a ověřit verzi rails:
```rails -v```

3) Pokud se vypíše verze Rails < 4, je potřeba stáhnou update:

```gem update rails --no-ri --no-rdoc```

4) Ověřit, že aplikace funguje v pořádku pomocí následujících kroků:

```
rails new railsgirls
cd railsgirls
rails server
```

5) Stáhnout a nainstalovat [Sublime Text 2](http://www.sublimetext.com/2).
6) Aktualizovat [Chrome](http://guides.railsgirls.com/install/google.com/chrome) nebo jej stáhnout a nainstalovat.
7) Vytvořit účet na [Heroku](www.heroku.com)
8) Stáhnout a nainstalovat [Heroku Toolbelt](https://toolbelt.heroku.com/windows) + vyzkoušet vytvoření a deploy aplikace


##Časté problémy a jak jim předejít

1) V minulosti se stávalo, že byl problém s instalací na počítačích, kde byla diakritika v uživatelském jméně - 
před instalací zkontrolujte jméno uživatele a v případě nutnosti vytvořte jiného bez diakritiky.