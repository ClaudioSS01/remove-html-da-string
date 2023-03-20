# remove-html-da-string
# remove tags da string
# remove html da string usando javascript js
```
                    //remove todo html e todas as tags script e style
                    const removeTags = (html) => {
                        const regex = /<script\b[^<]*(?:(?!<\/script>)<[^<]*)*<\/script>|<style\b[^<]*(?:(?!<\/style>)<[^<]*)*<\/style>|<[^>]*>/gm;
                        const result = html.replaceAll(regex, '');
                        return result;
                      };

                      const result__ = removeTags(html_bruto);
```
