# pod-test-files
Staging area so Runpod pods can fetch training files. Contents are our own generated pictures (Boogu-Image-0.1 Turbo / Edit, Apache-2.0) and LoRAs trained on them; nothing from Qwen, Meshy or game assets.
- `pairs/`: low poly conversion pairs (source + target) from lanes of 2026-10-02; `keep_relaxed.txt` / `keep_B.txt` list the pairs that passed the filter; score CSVs.
- `lora_a/`, `lora_b/`: Boogu-Image-0.1-Edit LoRAs (epoch-5.safetensors) that turn a picture into low poly from one plain sentence.
Raw URL form: https://raw.githubusercontent.com/imexotoo-commits/pod-test-files/main/<path>
