# Ldoc css stylings

The style for ldoc css generation

## Requirements

- [ldoc](https://github.com/lunarmodules/ldoc)

## Recommend

Use with ldoc-custom command instead of ldoc command ofcourse. It just a extension of ldoc command with this style

## Preview

![preview1](./docs/readme/preview1.png)
![preview2](./docs/readme/preview2.png)
![preview3](./docs/readme/preview3.png)

## Instllation

```bash
git clone https://github.com/sontungexpt/ldoc-css-styles.git && cd ldoc-css-styles

# If you want to use ldoc-custom command to generate css
# If you use ldoc-custom instead of ldoc, you can fix some bugs about html generation of ldoc
# It may be need sudo
# If you don't want to use ldoc-custom, you can skip two lines below
cp ldoc-custom /usr/bin/
ldoc-custom -h # to see help


# if you use ldoc-custom, you may not need to use this command because ldoc-custom will do it for you
cp ldoc.css your-project-path
```

## Contributions

If you find any issues with this configuration or would like to contribute, please feel free to submit a pull request or open an issue.

## License

This configuration is released under the GNU GENERAL PUBLIC LICENSE.
