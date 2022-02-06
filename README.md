# Implementation status of [extensions](https://clangd.llvm.org/extensions)
 - [ ] Memory usage
 - [ ] AST
 - [x] Symbol info request (implemented)
 - [x] Type hierarchy (implemented)
 - [x] Inlay hints (implemented)
 - [x] Switch between source/header (nvim-lspconfig already does this)
 - [x] File status (see lsp-status.nvim)
 - [x] Compilation commands (can be specified in lspconfig `init_options`)
 - [ ] Force diagnostics generation (look into this)
 - [ ] Code completion scores (look into this)
 - [-] Diagnostic categories (out of scope)
 - [-] Inline fixes for diagnostics (out of scope)