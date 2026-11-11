# XcrudRevolution

**XcrudRevolution** is a PHP 8 CRUD library and the successor to xCRUD 1.x. One line of PHP gives a complete data grid with forms, validation, relations, permissions and export.

- No dependencies, no jQuery
- Works on phones (the grid becomes cards on small screens)
- Built to target WCAG 2.2 AA accessibility
- Prepared queries: values never enter the SQL
- Real PHP callables and events for callbacks

🌐 Website: https://xcrudrevolution.com

> This repository contains no source code. XcrudRevolution is a commercial library; this page only points to the official site, demo, documentation and migration guide.

## Links

- **Live demo:** https://xcrudrevolution.com/en/demo
- **Documentation:** https://xcrudrevolution.com/en/docs
- **Migrating from xCRUD 1.x:** https://xcrudrevolution.com/en/migrate
- **xCRUD 1.x vs XcrudRevolution:** https://xcrudrevolution.com/en/compare/xcrud
- **Pricing:** https://xcrudrevolution.com/en/pricing
- **Community forum:** https://xcrud.me/

## Successor to xCRUD 1.x

xCRUD 1.6.26 (source dated March 2015) stops on PHP 8 because `get_magic_quotes_runtime()` no longer exists. XcrudRevolution is rewritten for PHP 8.

| | xCRUD 1.x | XcrudRevolution |
|---|---|---|
| PHP | Stops on PHP 8 | PHP 8.3 or 8.4 (ionCube Loader) |
| Databases | MySQL only, through mysqli | 7 databases, tested on real servers |
| Queries | Built by joining strings, values cleaned by `escape()` | Prepared queries: values never enter the SQL |
| Running values as code | `pass_var(…, $eval = true)` runs the value as PHP | Gone |
| Callbacks | A function name as text, plus a file to include | Real PHP callables and events |
| Front end | jQuery, jQuery UI, jCrop and Bootstrap 3.0.2 | Its own JavaScript and CSS |
| Errors | Forces `display_errors` on | Your error settings stay yours |
| Credentials | Plain text in `xcrud_config.php` | You pass a connection |

Full comparison: https://xcrudrevolution.com/en/compare/xcrud

## Editions and prices

The library is licensed per project (production domain), not per developer.

| Edition | Price | Production domains |
|---|---|---|
| Basic | €149.00 | 1 |
| Pro | €349.00 | 5 |
| Pro Agency | €899.00 | 10 |

Every edition includes a license that never expires, 12 months of updates, 12 months of support and commercial use. Your code keeps working even if you never renew.

**Xcrud AI** (optional, separate from the library license): 500 credits €49.00 · 2,000 credits €179.00 · 10,000 credits €790.00.

Current prices: https://xcrudrevolution.com/en/pricing/library · https://xcrudrevolution.com/en/pricing/ai

## Integrations

Works in plain PHP. A Laravel package and a WordPress plugin are planned, not yet released: https://xcrudrevolution.com/en/integrations
