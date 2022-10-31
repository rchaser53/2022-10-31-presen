wasm-pack --wbg-args '--reference-types'


reference typeの説明


wasm-packがwasm-bindgenに引数を渡す手段がない
  - やる気もなさそう
  - https://github.com/rustwasm/wasm-pack/pull/937


cargo install wasm-bindgen-cli

wasm-bindgen target/wasm32-unknown-unknown/debug/wasm_game_of_life.wasm --target web --reference-types --out-dir ./test-dir