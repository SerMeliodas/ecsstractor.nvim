# eCSStractor for nvim

## Instaling

```
'SerMeliodas/ecsstractor.nvim'
```

Just bind a plugin command to your preferd keymap and you can use it.

```
vim.api.nvim_set_keymap('v', '<Leader>ett', ":lua require'ecsstractor'.ecsstractor()<CR>",{})
```

## Using


Select the html code with bem classes and use your keymap, generated bem scss code copied to your clipboard.
