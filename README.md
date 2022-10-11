# Symfony Recipes

Custom recipes for Symfony Flex.

## Add recipes

Execute this to enable custom flex recipes:

```console
$ composer config --json extra.symfony.endpoint '["https://api.github.com/repos/jawira/recipes/contents/index.json","flex://defaults"]'
$ composer config --json extra.symfony.allow-contrib true
```

## References

* <https://github.com/symfony/recipes/blob/main/README.rst>
* <https://symfony.com/doc/current/setup/flex_private_recipes.html>
* <https://github.com/NimZero/FlexRecipes>
