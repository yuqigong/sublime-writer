# Sublime Wtiter

> For geeker, best writing is Sublime.
>
> by @Richie

## Plugs

- "All Autocomplete"
- "AutoFileName"
- "BracketHighlighter"
- "ConvertToUTF8"
- "Evernote"
- "GitHub Markdown Snippets"
- "MarkdownEditing"
- "MarkdownTOC"
- "Material Theme"
- "OmniMarkupPreviewer"
- "SideBarEnhancements"
- "TrailingSpaces"
- "Typewriter"
- "Surround"

## Usage

> note: First of all, install package control.

**Install Package Control**

```python
import urllib.request,os,hashlib; h = 'df21e130d211cfc94d9b0905775a7c0f' + '1e3d39e33b79698005270310898eea76'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

**Clone**

`git clone https://github.com/yuqigong/sublime-config.git ~/yourpath/Sublime`

**OS X**

> note: Then, Close Sublime Text be must.

```Shell
cd ~/yourpath/Sublime
cp -ri ./ ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
```

> note: Once again, restart Sublime Text. Successful installation.

**Dropbox** *(Optional)*

```Shell
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
mkdir ~/Dropbox/Sublime
mv User ~/Dropbox/Sublime/
ln -s ~/Dropbox/Sublime/User
```

**Other equipment**

```Shell
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
rm -r User
ln -s ~/Dropbox/Sublime/User
```

**Activate the theme**

```json
"color_scheme": "Packages/Material Theme/schemes/Material-Theme.tmTheme",
"theme": "Material-Theme.sublime-theme",
```

> note: Restart Sublime Text after activating the theme.

**Reminders**

Open the `Evernote.sublime-settings`, change them:

```json
{
    "noteStoreUrl": "yourNoteStoreUrl",
    "token": "yourToken"
}
```

**Reference**

[Sublime Syncing](https://packagecontrol.io/docs/syncing)

[Material theme](https://github.com/equinusocio/material-theme#activate-the-theme)

[Sublime Evernote](https://github.com/bordaigorl/sublime-evernote#first-use)

**Update**

> 2017-01-18

- Add Surround.
- Add Other equipment.

**License MIT**
