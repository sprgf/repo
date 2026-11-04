# repo

Personal Cydia repository by sprgf.

Classic-style repository intended for legacy Cydia clients, including iOS 6.1.3 on iPhone 4S.

## Repository layout
- `debs/` — Debian packages (`.deb`)
- `depictions/` — package descriptions
- `Packages` — APT package index
- `Packages.tar.bz2` — compressed package index used by this template
- `Release` — APT repository metadata
- `repo.xml` — repository metadata for the template
- `CydiaIcon.png` — repository icon
- `index.html` — classic landing page

Do not add packages until they have been built for the correct device architecture and tested for iOS 6 compatibility.
