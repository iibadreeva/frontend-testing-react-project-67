### Hexlet tests and linter status:
[![Actions Status](https://github.com/iibadreeva/frontend-testing-react-project-67/workflows/hexlet-check/badge.svg)](https://github.com/iibadreeva/frontend-testing-react-project-67/actions)

## Подсказки
- Для работы с файлами, используйте https://nodejs.org/api/fs.html#fs_fs_promises_api
- Тесты должны быть изолированы друг от друга. Для этого каждая загрузка должна выполняться в своей временной директории: await fs.mkdtemp(path.join(os.tmpdir(), 'page-loader-')); (в хуке beforeEach())
- Для общего кода в тестах (особенно с побочными эффектами) используются хуки beforeAll() и beforeEach()
- Тестировать работу через cli не нужно

