osx-vlgothic-fonts
==================

An Ansible role to install VLGothic fonts.

Requirements
------------

None.

Role Variables
--------------

- osx_vlgothic_fonts_download_url: http://sourceforge.jp/frs/redir.php?m=iij&f=%2Fvlgothic%2F61731%2FVLGothic-20140801.zip
- osx_vlgothic_fonts_zip_filename: VLGothic-20140801.zip
- osx_vlgothic_fonts_creates_font_filename: VL-Gothic-Regular.ttf
- osx_vlgothic_fonts_font_filenames:
  - VL-Gothic-Regular.ttf
  - VL-PGothic-Regular.ttf
- osx_vlgothic_fonts_download_dir: ~/Downloads
- osx_vlgothic_fonts_install_dir: ~/Library/Fonts

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
        - hnakamur.osx-vlgothic-fonts

License
-------

MIT

Author Information
------------------

[Hiroaki Nakamura]( http://hnakamur.github.io/ )
