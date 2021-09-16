# Deno Standard Library Snippets

Standard library import autocompletions for Deno in VS Code"

## How to use

Type `deno-` + standard library name like `version`, press `enter`, and the import snippet unfolds.

Type `deno-ex-` + standard library name like `version`, press `enter`, and the example code snippet unfolds.

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (macOS) to activate snippets from within the editor.

## Install instructions

Install via Extension Marketplace

- Search for the Extension `Deno Standard Library Snippets` and install.

## Features

Autocomplete for Modules below using tag: `deno-`.

### Import Snippets:

| Snippet                         | Renders                                                                       |
| ------------------------------- | ----------------------------------------------------------------------------- |
| `deno-archive-tar`              | import { $1 } from 'https://deno.land/std/archive/tar.ts'              |
| `deno-async-deferred`           | import { $1 } from 'https://deno.land/std/async/deferred.ts'           |
| `deno-async-delay`              | import { $1 } from 'https://deno.land/std/async/delay.ts'              |
| `deno-async-mod`                | import { $1 } from 'https://deno.land/std/async/mod.ts'                |
| `deno-async-mux_async_iterator` | import { $1 } from 'https://deno.land/std/async/mux_async_iterator.ts' |
| `deno-async-pool`               | import { $1 } from 'https://deno.land/std/async/pool.ts'               |
| `deno-async-test`               | import { $1 } from 'https://deno.land/std/async/test.ts'               |
| `deno-bytes-mod`                | import { $1 } from 'https://deno.land/std/bytes/mod.ts'                |
| `deno-bytes-test`               | import { $1 } from 'https://deno.land/std/bytes/test.ts'               |
| `deno-datetime-formatter`       | import { $1 } from 'https://deno.land/std/datetime/formatter.ts'       |
| `deno-datetime-mod`             | import { $1 } from 'https://deno.land/std/datetime/mod.ts'             |
| `deno-datetime-test`            | import { $1 } from 'https://deno.land/std/datetime/test.ts'            |
| `deno-datetime-tokenizer`       | import { $1 } from 'https://deno.land/std/datetime/tokenizer.ts'       |
| `deno-encoding-ascii85`         | import { $1 } from 'https://deno.land/std/encoding/ascii85.ts'         |
| `deno-encoding-base32`          | import { $1 } from 'https://deno.land/std/encoding/base32.ts'          |
| `deno-encoding-base64`          | import { $1 } from 'https://deno.land/std/encoding/base64.ts'          |
| `deno-encoding-base64url`       | import { $1 } from 'https://deno.land/std/encoding/base64url.ts'       |
| `deno-encoding-binary`          | import { $1 } from 'https://deno.land/std/encoding/binary.ts'          |
| `deno-encoding-csv`             | import { $1 } from 'https://deno.land/std/encoding/csv.ts'             |
| `deno-encoding-csv_stringify`   | import { $1 } from 'https://deno.land/std/encoding/csv_stringify.ts'   |
| `deno-encoding-hex`             | import { $1 } from 'https://deno.land/std/encoding/hex.ts'             |
| `deno-encoding-toml`            | import { $1 } from 'https://deno.land/std/encoding/toml.ts'            |
| `deno-encoding-yaml`            | import { $1 } from 'https://deno.land/std/encoding/yaml.ts'            |
| `deno-examples-cat`             | import { $1 } from 'https://deno.land/std/examples/cat.ts'             |
| `deno-examples-catj`            | import { $1 } from 'https://deno.land/std/examples/catj.ts'            |
| `deno-examples-colors`          | import { $1 } from 'https://deno.land/std/examples/colors.ts'          |
| `deno-examples-curl`            | import { $1 } from 'https://deno.land/std/examples/curl.ts'            |
| `deno-examples-echo_server`     | import { $1 } from 'https://deno.land/std/examples/echo_server.ts'     |
| `deno-examples-flags`           | import { $1 } from 'https://deno.land/std/examples/flags.ts'           |
| `deno-examples-gist`            | import { $1 } from 'https://deno.land/std/examples/gist.ts'            |
| `deno-examples-test`            | import { $1 } from 'https://deno.land/std/examples/test.ts'            |
| `deno-examples-welcome`         | import { $1 } from 'https://deno.land/std/examples/welcome.ts'         |
| `deno-examples-xeval`           | import { $1 } from 'https://deno.land/std/examples/xeval.ts'           |
| `deno-flags-mod`                | import { $1 } from 'https://deno.land/std/flags/mod.ts'                |
| `deno-flags-test`               | import { $1 } from 'https://deno.land/std/flags/test.ts'               |
| `deno-fmt-colors`               | import { $1 } from 'https://deno.land/std/fmt/colors.ts'               |
| `deno-fmt-printf`               | import { $1 } from 'https://deno.land/std/fmt/printf.ts'               |
| `deno-fs-copy`                  | import { $1 } from 'https://deno.land/std/fs/copy.ts'                  |
| `deno-fs-empty_dir`             | import { $1 } from 'https://deno.land/std/fs/empty_dir.ts'             |
| `deno-fs-ensure_dir`            | import { $1 } from 'https://deno.land/std/fs/ensure_dir.ts'            |
| `deno-fs-ensure_file`           | import { $1 } from 'https://deno.land/std/fs/ensure_file.ts'           |
| `deno-fs-ensure_link`           | import { $1 } from 'https://deno.land/std/fs/ensure_link.ts'           |
| `deno-fs-ensure_symlink`        | import { $1 } from 'https://deno.land/std/fs/ensure_symlink.ts'        |
| `deno-fs-eol`                   | import { $1 } from 'https://deno.land/std/fs/eol.ts'                   |
| `deno-fs-exists`                | import { $1 } from 'https://deno.land/std/fs/exists.ts'                |
| `deno-fs-expand_glob`           | import { $1 } from 'https://deno.land/std/fs/expand_glob.ts'           |
| `deno-fs-mod`                   | import { $1 } from 'https://deno.land/std/fs/mod.ts'                   |
| `deno-fs-move`                  | import { $1 } from 'https://deno.land/std/fs/move.ts'                  |
| `deno-fs-test`                  | import { $1 } from 'https://deno.land/std/fs/test.ts'                  |
| `deno-fs-walk`                  | import { $1 } from 'https://deno.land/std/fs/walk.ts'                  |
| `deno-hash-fnv`                 | import { $1 } from 'https://deno.land/std/hash/fnv.ts'                 |
| `deno-hash-hasher`              | import { $1 } from 'https://deno.land/std/hash/hasher.ts'              |
| `deno-hash-md5`                 | import { $1 } from 'https://deno.land/std/hash/md5.ts'                 |
| `deno-hash-mod`                 | import { $1 } from 'https://deno.land/std/hash/mod.ts'                 |
| `deno-hash-sha1`                | import { $1 } from 'https://deno.land/std/hash/sha1.ts'                |
| `deno-hash-sha256`              | import { $1 } from 'https://deno.land/std/hash/sha256.ts'              |
| `deno-hash-sha3`                | import { $1 } from 'https://deno.land/std/hash/sha3.ts'                |
| `deno-hash-sha512`              | import { $1 } from 'https://deno.land/std/hash/sha512.ts'              |
| `deno-hash-test`                | import { $1 } from 'https://deno.land/std/hash/test.ts'                |
| `deno-http-bench`               | import { $1 } from 'https://deno.land/std/http/bench.ts'               |
| `deno-http-cookie`              | import { $1 } from 'https://deno.land/std/http/cookie.ts'              |
| `deno-http-file_server`         | import { $1 } from 'https://deno.land/std/http/file_server.ts'         |
| `deno-http-http_status`         | import { $1 } from 'https://deno.land/std/http/http_status.ts'         |
| `deno-http-mod`                 | import { $1 } from 'https://deno.land/std/http/mod.ts'                 |
| `deno-http-racing_server`       | import { $1 } from 'https://deno.land/std/http/racing_server.ts'       |
| `deno-http-server`              | import { $1 } from 'https://deno.land/std/http/server.ts'              |
| `deno-http-test`                | import { $1 } from 'https://deno.land/std/http/test.ts'                |
| `deno-io-buffer`                | import { $1 } from 'https://deno.land/std/io/buffer.ts'                |
| `deno-io-bufio`                 | import { $1 } from 'https://deno.land/std/io/bufio.ts'                 |
| `deno-io-ioutil`                | import { $1 } from 'https://deno.land/std/io/ioutil.ts'                |
| `deno-io-mod`                   | import { $1 } from 'https://deno.land/std/io/mod.ts'                   |
| `deno-io-readers`               | import { $1 } from 'https://deno.land/std/io/readers.ts'               |
| `deno-io-streams`               | import { $1 } from 'https://deno.land/std/io/streams.ts'               |
| `deno-io-test`                  | import { $1 } from 'https://deno.land/std/io/test.ts'                  |
| `deno-io-util`                  | import { $1 } from 'https://deno.land/std/io/util.ts'                  |
| `deno-io-writers`               | import { $1 } from 'https://deno.land/std/io/writers.ts'               |
| `deno-log-handlers`             | import { $1 } from 'https://deno.land/std/log/handlers.ts'             |
| `deno-log-levels`               | import { $1 } from 'https://deno.land/std/log/levels.ts'               |
| `deno-log-logger`               | import { $1 } from 'https://deno.land/std/log/logger.ts'               |
| `deno-log-mod`                  | import { $1 } from 'https://deno.land/std/log/mod.ts'                  |
| `deno-log-test`                 | import { $1 } from 'https://deno.land/std/log/test.ts'                 |
| `deno-mime-mod`                 | import { $1 } from 'https://deno.land/std/mime/mod.ts'                 |
| `deno-mime-multipart`           | import { $1 } from 'https://deno.land/std/mime/multipart.ts'           |
| `deno-mime-test`                | import { $1 } from 'https://deno.land/std/mime/test.ts'                |
| `deno-node-assert`              | import { $1 } from 'https://deno.land/std/node/assert.ts'              |
| `deno-node-assertion_error`     | import { $1 } from 'https://deno.land/std/node/assertion_error.ts'     |
| `deno-node-buffer`              | import { $1 } from 'https://deno.land/std/node/buffer.ts'              |
| `deno-node-cli`                 | import { $1 } from 'https://deno.land/std/node/cli.ts'                 |
| `deno-node-constants`           | import { $1 } from 'https://deno.land/std/node/constants.ts'           |
| `deno-node-crypto`              | import { $1 } from 'https://deno.land/std/node/crypto.ts'              |
| `deno-node-events`              | import { $1 } from 'https://deno.land/std/node/events.ts'              |
| `deno-node-fs`                  | import { $1 } from 'https://deno.land/std/node/fs.ts'                  |
| `deno-node-global`              | import { $1 } from 'https://deno.land/std/node/global.ts'              |
| `deno-node-module`              | import { $1 } from 'https://deno.land/std/node/module.ts'              |
| `deno-node-os`                  | import { $1 } from 'https://deno.land/std/node/os.ts'                  |
| `deno-node-path`                | import { $1 } from 'https://deno.land/std/node/path.ts'                |
| `deno-node-process`             | import { $1 } from 'https://deno.land/std/node/process.ts'             |
| `deno-node-querystring`         | import { $1 } from 'https://deno.land/std/node/querystring.ts'         |
| `deno-node-stream`              | import { $1 } from 'https://deno.land/std/node/stream.ts'              |
| `deno-node-string_decoder`      | import { $1 } from 'https://deno.land/std/node/string_decoder.ts'      |
| `deno-node-timers`              | import { $1 } from 'https://deno.land/std/node/timers.ts'              |
| `deno-node-tty`                 | import { $1 } from 'https://deno.land/std/node/tty.ts'                 |
| `deno-node-url`                 | import { $1 } from 'https://deno.land/std/node/url.ts'                 |
| `deno-node-util`                | import { $1 } from 'https://deno.land/std/node/util.ts'                |
| `deno-path-common`              | import { $1 } from 'https://deno.land/std/path/common.ts'              |
| `deno-path-glob`                | import { $1 } from 'https://deno.land/std/path/glob.ts'                |
| `deno-path-mod`                 | import { $1 } from 'https://deno.land/std/path/mod.ts'                 |
| `deno-path-posix`               | import { $1 } from 'https://deno.land/std/path/posix.ts'               |
| `deno-path-separator`           | import { $1 } from 'https://deno.land/std/path/separator.ts'           |
| `deno-path-test`                | import { $1 } from 'https://deno.land/std/path/test.ts'                |
| `deno-path-win32`               | import { $1 } from 'https://deno.land/std/path/win32.ts'               |
| `deno-permissions-mod`          | import { $1 } from 'https://deno.land/std/permissions/mod.ts'          |
| `deno-permissions-test`         | import { $1 } from 'https://deno.land/std/permissions/test.ts'         |
| `deno-signal-mod`               | import { $1 } from 'https://deno.land/std/signal/mod.ts'               |
| `deno-signal-test`              | import { $1 } from 'https://deno.land/std/signal/test.ts'              |
| `deno-testing-asserts`          | import { $1 } from 'https://deno.land/std/testing/asserts.ts'          |
| `deno-testing-bench`            | import { $1 } from 'https://deno.land/std/testing/bench.ts'            |
| `deno-testing-bench_example`    | import { $1 } from 'https://deno.land/std/testing/bench_example.ts'    |
| `deno-textproto-mod`            | import { $1 } from 'https://deno.land/std/textproto/mod.ts'            |
| `deno-textproto-test`           | import { $1 } from 'https://deno.land/std/textproto/test.ts'           |
| `deno-uuid-mod`                 | import { $1 } from 'https://deno.land/std/uuid/mod.ts'                 |
| `deno-uuid-test`                | import { $1 } from 'https://deno.land/std/uuid/test.ts'                |
| `deno-uuid-v1`                  | import { $1 } from 'https://deno.land/std/uuid/v1.ts'                  |
| `deno-uuid-v4`                  | import { $1 } from 'https://deno.land/std/uuid/v4.ts'                  |
| `deno-uuid-v5`                  | import { $1 } from 'https://deno.land/std/uuid/v5.ts'                  |
| `deno-wasi-snapshot_preview1`   | import { $1 } from 'https://deno.land/std/wasi/snapshot_preview1.ts'   |
| `deno-ws-example_server`        | import { $1 } from 'https://deno.land/std/ws/example_server.ts'        |
| `deno-ws-mod`                   | import { $1 } from 'https://deno.land/std/ws/mod.ts'                   |
| `deno-ws-test`                  | import { $1 } from 'https://deno.land/std/ws/test.ts'                  |

### Example Snippets:

| Snippet                              |
| ------------------------------------ |
| `deno-ex-archive-tar`                |
| `deno-ex-archive-untar`              |
| `deno-ex-async-deferred`             |
| `deno-ex-async-delay`                |
| `deno-ex-async-muxAsyncIterator`     |
| `deno-ex-async-pooledMap`            |
| `deno-ex-bytes-indexOf`              |
| `deno-ex-bytes-lastIndexOf`          |
| `deno-ex-bytes-equals`               |
| `deno-ex-bytes-startsWith`           |
| `deno-ex-bytes-endsWith`             |
| `deno-ex-bytes-repeat`               |
| `deno-ex-bytes-concat`               |
| `deno-ex-bytes-contains`             |
| `deno-ex-bytes-copy`                 |
| `deno-ex-datetime-parse`             |
| `deno-ex-datetime-format`            |
| `deno-ex-datetime-dayOfYear`         |
| `deno-ex-datetime-weekOfYear`        |
| `deno-ex-datetime-toIMF`             |
| `deno-ex-datetime-isLeap`            |
| `deno-ex-datetime-difference`        |
| `deno-ex-datetime-SECOND`            |
| `deno-ex-datetime-MINUTE`            |
| `deno-ex-datetime-HOUR`              |
| `deno-ex-datetime-DAY`               |
| `deno-ex-datetime-WEEK`              |
| `deno-ex-fs-emptyDir`                |
| `deno-ex-fs-ensureDir`               |
| `deno-ex-fs-ensureFile`              |
| `deno-ex-fs-ensureSymlink`           |
| `deno-ex-fs-EOL`                     |
| `deno-ex-fs-exists`                  |
| `deno-ex-fs-move`                    |
| `deno-ex-fs-copy`                    |
| `deno-ex-fs-walk`                    |
| `deno-ex-fs-expandGlob`              |
| `deno-ex-fs-expandGlobSync`          |
| `deno-ex-flags`                      |
| `deno-ex-fmt`                        |
| `deno-ex-hash`                       |
| `deno-ex-http-server`                |
| `deno-ex-http-cookie`                |
| `deno-ex-io-stringReader`            |
| `deno-ex-io-stringWriter`            |
| `deno-ex-io-readerFromStreamReader`  |
| `deno-ex-io-writerFromStreamWriter`  |
| `deno-ex-log`                        |
| `deno-ex-node`                       |
| `deno-ex-signal`                     |
| `deno-ex-testing-assertEquals`       |
| `deno-ex-testing-assertStrictEquals` |
| `deno-ex-testing-assertThrows`       |
| `deno-ex-testing-assertThrowsAsync`  |
| `deno-ex-uuid`                       |
| `deno-ex-wasi`                       |
| `deno-ex-ws`                         |
