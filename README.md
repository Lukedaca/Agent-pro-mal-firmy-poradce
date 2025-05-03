# AI Poradce pro malé firmy

Interaktivní webová aplikace, která využívá GPT-4 pro poskytování personalizovaných rad a doporučení malým firmám a podnikatelům v České republice.

![Screenshot aplikace](screenshot.png)

## 🌟 Funkce

- **Personalizované poradenství** - Přizpůsobené rady dle oboru podnikání
- **Hlasové ovládání** - Zadávejte dotazy hlasem pomocí rozpoznávání řeči
- **Předčítání odpovědí** - Nechte si odpovědi přečíst pomocí syntézy řeči
- **Export odpovědí** - Stahujte odpovědi jako PDF nebo TXT soubory
- **Adaptivní paměť** - AI si pamatuje předchozí konverzace a učí se z nich
- **Různé tóny odpovědí** - Vyberte si mezi stručným, detailním, motivačním nebo odborným stylem

## 🧠 Inteligentní učení

Aplikace obsahuje pokročilý systém paměti a adaptivního učení:

- **Kontextuální odpovědi** - AI využívá předchozí konverzace k poskytování přesnějších rad
- **Extrakce znalostí** - Automaticky identifikuje a ukládá klíčové informace z odpovědí
- **Statistiky a analýza** - Sleduje nejčastější témata a otázky
- **Persistentní paměť** - Znalosti jsou uloženy v prohlížeči a přetrvávají mezi relacemi
- **Správa dat** - Možnost exportu nebo smazání uložených znalostí

## 🚀 Jak začít

1. Otevřete `index.html` ve vašem prohlížeči nebo nahrajte soubory na webový server
2. Klikněte na "⚙️ Nastavení" a zadejte váš OpenAI API klíč
3. Vyberte obor podnikání nebo zadejte vlastní
4. Napište otázku nebo klikněte na "🎤 Zadat hlasem" pro hlasový vstup
5. Zvolte preferovaný tón odpovědi
6. Klikněte na "Zeptej se" a počkejte na odpověď

## 📋 Požadavky

- Webový prohlížeč s podporou JavaScript
- Platný OpenAI API klíč s přístupem k modelu GPT-4
- Pro hlasové funkce je vyžadován prohlížeč s podporou Web Speech API (Chrome, Edge, Safari)

## 🔧 Technologie

- HTML5, CSS3, JavaScript
- [Tailwind CSS](https://tailwindcss.com/) pro styling
- [jsPDF](https://github.com/parallax/jsPDF) pro generování PDF
- Web Speech API pro hlasové vstupy a výstupy
- LocalStorage pro ukládání paměti agenta

## 💾 Instalace

```bash
# Klonujte repozitář
git clone https://github.com/vaseuzivatelskejmeno/ai-poradce.git

# Přejděte do adresáře projektu
cd ai-poradce

# Otevřete index.html ve vašem oblíbeném prohlížeči
```

## 🔒 Soukromí a bezpečnost

- Váš API klíč je uložen pouze lokálně ve vašem prohlížeči
- Veškeré konverzace a data jsou zpracovávány a ukládány pouze na vašem zařízení
- Žádná data nejsou odesílána na servery kromě požadavků na OpenAI API

## ⚠️ Omezení

- Aplikace vyžaduje připojení k internetu pro komunikaci s OpenAI API
- Kvalita odpovědí závisí na kvalitě dotazu a relevantnosti pro váš obor
- API klíč není součástí tohoto projektu a musí být zakoupen samostatně od OpenAI

## 📜 Licence

Tento projekt je licencován pod [MIT licencí](LICENSE).

## 👨‍💻 Přispívání

Příspěvky jsou vítány! Pokud máte nápady na vylepšení:

1. Forkněte repozitář
2. Vytvořte větev pro vaši funkci (`git checkout -b feature/amazingFeature`)
3. Commitněte vaše změny (`git commit -m 'Add some amazingFeature'`)
4. Pushněte do větve (`git push origin feature/amazingFeature`)
5. Otevřete Pull Request

## 📬 Kontakt

Autor : Lukáš Drštička lukas.drsticka@gmail.com
