# Learning Notes of  Deno 

The list of deno releases.

[v0.1.6](https://github.com/denoland/deno/releases/tag/v0.1.6)
- Adds deno.stdin, deno.stdout, deno.stderr, deno.open(), deno.write(),
  deno.read(), deno.Reader, deno.Writer, deno.copy() #846
- Print 'Compiling' when compiling TS.
- Support zero-copy for writeFile() writeFileSync() #838
- Fixes eval error bug #837
- Make Deno multithreaded #782
- console.warn() goes to stderr #810
- Add deno.readlink()/readlinkSync() #797
- Add --recompile flag #801
- Use constructor.name to print out function type #664
- Rename deno.argv to deno.args
- Add deno.trace() #795
- Continuous benchmarks https://denoland.github.io/deno/

[v0.1.5](https://github.com/denoland/deno/releases/tag/v0.1.5)
- Add atob() btoa() #776
- Add deno.arch deno.platform #773
- Add deno.symlink() and deno.symlinkSync() #742
- Add deno.mkdir() and deno.mkdirSync() #746
- Add deno.makeTempDir() #740
- Improvements to FileInfo interface #765, #761
- Add fetch.blob()
- Upgrade V8 to 7.0.276.15
- Upgrade Rust crates
##### Install with Python:
```
curl -sSf https://raw.githubusercontent.com/denoland/deno_install/master/install.py | python
```
##### Install with PowerShell:
```
iex (iwr https://raw.githubusercontent.com/denoland/deno_install/master/install.ps1)
```
_Note: Depending on your security settings, you may have to run Set-ExecutionPolicy RemoteSigned -Scope CurrentUser first to allow downloaded scripts to be executed._

Try it:
```
> deno http://deno.land/thumb.ts
```




