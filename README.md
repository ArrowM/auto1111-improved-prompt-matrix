# ⚠️ This script has been deprecated ⚠️
Please use the integrated [XYZ grid](https://github.com/AUTOMATIC1111/stable-diffusion-webui/blob/master/scripts/xyz_grid.py) or the [sd-dynamic-prompts](https://github.com/adieyal/sd-dynamic-prompts) extension instead.

---

## auto1111-improved-prompt-matrix

This script is [advanced-prompt-matrix](https://github.com/GRMrGecko/stable-diffusion-webui-automatic/blob/advanced_matrix/scripts/advanced_prompt_matrix.py) modified to support `batch count`.

### Usage

Use `<` `>` to create a group of alternate texts. Separate text options with `|`. Multiple groups and multiple options can be used. For example:

An input of `a <corgi|cat> wearing <goggles|a hat>`  
Will output 4 prompts: `a corgi wearing goggles`, `a corgi wearing a hat`, `a cat wearing goggles`, `a cat wearing a hat`

Each output prompt will be generated for each seed when using a `batch count` > 1. `batch size` is ignored.
