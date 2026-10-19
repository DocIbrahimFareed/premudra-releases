# PREMUDRA — releases

This repository only publishes **signed update files** of the PREMUDRA research workstation (Clinical Research Workstation).
It contains no source code, no study data and no patient data. The program's source lives in a separate private repository.

## How an update works

- An update is one `.zip` file attached to a release of this repository.
- Inside, `update.json` lists every changed file with its SHA-256, and `update.json.sig` is an Ed25519 signature made with the developer's key.
- The installed program applies an update only after the signature verifies against the public key built into it. The signing key is never published.
- Applying an update keeps the study data untouched; a change of the study structure is offered at the next start.

No update is published here yet.

## Не открытое ПО

Этот репозиторий — только место для подписанных файлов обновлений программы PREMUDRA. Исходного кода, данных исследования и данных пациентов здесь нет.
