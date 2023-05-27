# Colin's PowerShell Module Template

I wrote so many modules that I wound up making this template so that I can get started faster.  Once you've started working:

1. Find and replace `$$$MODULE_NAME$$$` with the module's name.
2. Create a module manifest.
3. Create a source file in `src/`.
4. Put icons in `icon/`.
5. Generate documentation with platyPS.
6. Fill out the NEWS and CHANGELOG files.
7. Use New-Release.ps1 on a Windows machine to create a signed binary for the PowerShell Gallery.

## But I'm not Colin!

Then I hope you find this useful anyway.  I will not be accepting PRs on this, though.

Now delete this line and everything above it.

# $$$MODULE_NAME$$$

[![PowerShell Gallery Version](https://img.shields.io/powershellgallery/v/$$$MODULE_NAME$$$)
 ![PowerShell Gallery](https://img.shields.io/powershellgallery/p/$$$MODULE_NAME$$$)
 ![Download from PowerShell Gallery](https://img.shields.io/powershellgallery/dt/$$$MODULE_NAME$$$)
](https://www.powershellgallery.com/packages/$$$MODULE_NAME$$$/)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/rhymeswithmogul/$$$MODULE_NAME$$$/run-pester-tests.yaml)
[![Run Pester tests](https://github.com/rhymeswithmogul/$$$MODULE_NAME$$$/actions/workflows/run-pester-tests.yaml/badge.svg)](https://github.com/rhymeswithmogul/$$$MODULE_NAME$$$/actions/workflows/run-pester-tests.yaml)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

Describe the module.
