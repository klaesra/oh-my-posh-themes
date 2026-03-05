# oh-my-posh-themes

Custom [oh-my-posh](https://ohmyposh.dev) themes.

## atomic-breadcrumb

Based on the built-in [atomic](https://ohmyposh.dev/docs/themes#atomic) theme, with a custom breadcrumb-style path segment that shows:

- Drive letter + first folder
- Depth indicator (number of hidden intermediate folders)
- Current folder

### Usage

```powershell
oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/klaesra/oh-my-posh-themes/main/atomic-breadcrumb.omp.json' | Invoke-Expression
```
