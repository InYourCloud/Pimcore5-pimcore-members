# Upgrade Notes

#### Update from Version 2.2.0 to Version 2.2.1
- implemented [PackageVersionTrait](https://github.com/pimcore/pimcore/blob/master/lib/Extension/Bundle/Traits/PackageVersionTrait.php)

#### Update from Version 2.1.x to Version 2.2.0
- **[NEW FEATURE]**: Restriction Icons in Tree View. See [#63](https://github.com/dachcom-digital/pimcore-members/issues/63)
- Some Bugfixes

#### Update from Version 2.0.x to Version 2.1.0
- **[BC BREAK]**: Members does not include any routes automatically anymore! Please include the [routes manually](https://github.com/dachcom-digital/pimcore-members#route-installation) if needed.
- **[BC BREAK]**: Validation messages removed from `messages` domain. Read more about it [here](https://github.com/dachcom-digital/pimcore-members/issues/45).
- **[BC BREAK]**: Render Forms via Symfony Form Theme (Bootstrap4 by default). See [#41](https://github.com/dachcom-digital/pimcore-members/issues/41)
- **[NEW FEATURE]**: User deletion. See [#48](https://github.com/dachcom-digital/pimcore-members/issues/48)

#### Update from Version 1.x to Version 2.0.0
- TBD