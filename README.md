# Swa Dereva (Kumbukumbu)

Hazina hii ni **kumbukumbu** ya dereva wa Rust/LLVM wa lugha ya
[Swa](https://github.com/lugha-swa/swa) — mkusanyaji wa majaribio
uliojengwa kwa Rust, uliotumia LLVM kama backend.

## Kwa nini umehifadhiwa

Uamuzi wa 2026-08-19 (hati/mipaka.md, kipengele cha 6): mwisho wa
LLVM ni wa MAJARIBIO pekee. Mnyororo wa uzalishaji wa Swa ni
kujikusanya kabisa — baiti za mkono (kwanza, 393) hadi mbegu hadi
stage1 — bila Rust, bila LLVM, bila gcc, bila ld, bila clang,
bila libc.

Dereva huu ulitumikia kama:

1. Njia ya pili ya kukagua semantiki ya lugha (majaribio 232:
   146 ya maktaba, 85 ya ujumuishaji, 1 wa nyaraka).
2. Uthibitisho kwamba vipimo vyote viwili vinaelewa lugha moja.

Tarehe 2026-09-05, mradi mkuu umefikia hali ambapo mnyororo wa
Swa pekee unasimama yenyewe kwa ukamilifu (majaribio 304/304 ya
mnyororo, fixpoint sawa kwa baiti), na dereva umehamishiwa hapa
ili hazina kuu ibaki lugha moja tu: Swa.

Historia kamili ya mabadiliko yake ipo kwenye hazina kuu.

## Muundo

- `src/` — msimbo wa Rust (msomaji, mchanganuzi, IR, backend ya LLVM)
- `majaribio/integration.rs` — majaribio 85 ya ujumuishaji
- `gharama/jaribu-swa.sh` — kiendeshi cha majaribio (kinahitaji clang)
- `Cargo.toml` — jina la binary: `kande`

## Kuijenga (kwa kumbukumbu tu)

```
cargo build --release
cargo test
```

## Leseni

Apache-2.0 au MIT, kama hazina kuu.
