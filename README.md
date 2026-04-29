# Vylepšení bezpečnosti a správy uživatelských účtů na základní škole pomocí Azure Active Directory a Microsoft 365

Bakalářská práce — Bao Kieu Quang  
Univerzita Jana Evangelisty Purkyně v Ústí nad Labem, Přírodovědecká fakulta  
Studijní program: Aplikovaná informatika  
Vedoucí práce: Ing. Pavel Kuba, Ph.D.  
Rok: 2026

---

## O práci

Práce se zabývá návrhem a pilotním ověřením přechodu ze sdílených lokálních účtů na individuální cloudové identity spravované v Microsoft Entra ID na Základní škole Vinařská v Ústí nad Labem. Škola využívá licence Microsoft 365 Education A3, které poskytují přístup k nástrojům pro centrální správu identit a zařízení, avšak tyto nástroje nebyly dosud využívány.

Součástí práce je analýza současného stavu, architekturní návrh řešení, pilotní nasazení a konfigurační dokumentace určená pro správce a vedení školy.

---

## Struktura repozitáře

| Soubor | Popis |
|--------|-------|
| `ki-thesis.tex` | Zdrojový kód práce v LaTeXu |
| `thesis.bib` | Bibliografická databáze |
| `kitheses.cls` | Třída dokumentu (UJEP) |
| `LOGO_PRF_CZ_RGB_standard.jpg` | Logo fakulty |
| `Konfiguracni_dokumentace.pdf` | Konfigurační dokumentace pro správce školy |

---

## Překlad dokumentu

Dokument vyžaduje pdfLaTeX a balíček biblatex. Doporučený postup překladu:

```bash
pdflatex ki-thesis.tex
biber ki-thesis
pdflatex ki-thesis.tex
pdflatex ki-thesis.tex
```

Nebo použijte [Overleaf](https://www.overleaf.com) s nastaveným kompilátorem pdfLaTeX.

---

## Klíčová témata

- Microsoft Entra ID (dříve Azure Active Directory)
- Microsoft Intune — správa zařízení
- Vícefaktorové ověřování (MFA)
- Podmíněný přístup (Conditional Access)
- BitLocker — šifrování disků
- GDPR a ochrana osobních údajů ve školách
- Microsoft 365 Education A3

---

## Konfigurační dokumentace

Soubor `Konfiguracni_dokumentace.pdf` je praktická příručka pro IT administrátora a vedení školy. Obsahuje postupy pro správu uživatelů, řešení problémů s MFA, přehled nasazených politik Intune a scénář zapůjčeného notebooku.