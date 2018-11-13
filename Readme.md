
# Tinygo Import Report
This project imports each package in the stdlib and reports if it imports cleanly in tinygo.

| Package | Imported? |
| --- | --- |
| archive/tar |  [:x:](#archive/tar)  |
| archive/zip |  [:x:](#archive/zip)  |
| bufio |  :heavy_check_mark:  |
| bytes |  :heavy_check_mark:  |
| compress/bzip2 |  :heavy_check_mark:  |
| compress/flate |  [:x:](#compress/flate)  |
| compress/gzip |  [:x:](#compress/gzip)  |
| compress/lzw |  :heavy_check_mark:  |
| compress/zlib |  [:x:](#compress/zlib)  |
| container |  [:x:](#container)  |
| container/heap |  :heavy_check_mark:  |
| container/list |  :heavy_check_mark:  |
| container/ring |  :heavy_check_mark:  |
| context |  [:x:](#context)  |
| crypto |  [:x:](#crypto)  |
| crypto/aes |  :heavy_check_mark:  |
| crypto/cipher |  :heavy_check_mark:  |
| crypto/des |  :heavy_check_mark:  |
| crypto/dsa |  [:x:](#crypto/dsa)  |
| crypto/ecdsa |  [:x:](#crypto/ecdsa)  |
| crypto/elliptic |  [:x:](#crypto/elliptic)  |
| crypto/hmac |  :heavy_check_mark:  |
| crypto/md5 |  [:x:](#crypto/md5)  |
| crypto/rand |  [:x:](#crypto/rand)  |
| crypto/rc4 |  :heavy_check_mark:  |
| crypto/rsa |  [:x:](#crypto/rsa)  |
| crypto/sha1 |  [:x:](#crypto/sha1)  |
| crypto/sha256 |  [:x:](#crypto/sha256)  |
| crypto/sha512 |  [:x:](#crypto/sha512)  |
| crypto/subtle |  :heavy_check_mark:  |
| crypto/tls |  [:x:](#crypto/tls)  |
| crypto/x509/pkix |  [:x:](#crypto/x509/pkix)  |
| database/sql |  [:x:](#database/sql)  |
| database/sql/driver |  [:x:](#database/sql/driver)  |
| encoding |  :heavy_check_mark:  |
| encoding/ascii85 |  :heavy_check_mark:  |
| encoding/asn1 |  [:x:](#encoding/asn1)  |
| encoding/base32 |  [:x:](#encoding/base32)  |
| encoding/base64 |  [:x:](#encoding/base64)  |
| encoding/binary |  :heavy_check_mark:  |
| encoding/csv |  :heavy_check_mark:  |
| encoding/gob |  [:x:](#encoding/gob)  |
| encoding/hex |  :heavy_check_mark:  |
| encoding/json |  [:x:](#encoding/json)  |
| encoding/pem |  [:x:](#encoding/pem)  |
| encoding/xml |  [:x:](#encoding/xml)  |
| errors |  :heavy_check_mark:  |
| expvar |  [:x:](#expvar)  |
| flag |  [:x:](#flag)  |
| fmt |  :heavy_check_mark:  |
| hash |  :heavy_check_mark:  |
| hash/adler32 |  :heavy_check_mark:  |
| hash/crc32 |  [:x:](#hash/crc32)  |
| hash/crc64 |  [:x:](#hash/crc64)  |
| hash/fnv |  :heavy_check_mark:  |
| html |  [:x:](#html)  |
| html/template |  [:x:](#html/template)  |
| image |  [:x:](#image)  |
| image/color |  :heavy_check_mark:  |
| image/color/palette |  [:x:](#image/color/palette)  |
| image/draw |  [:x:](#image/draw)  |
| image/gif |  [:x:](#image/gif)  |
| image/jpeg |  [:x:](#image/jpeg)  |
| image/png |  [:x:](#image/png)  |
| index/suffixarray |  :heavy_check_mark:  |
| io |  :heavy_check_mark:  |
| io/ioutil |  :heavy_check_mark:  |
| log |  :heavy_check_mark:  |
| log/syslog |  [:x:](#log/syslog)  |
| math |  :heavy_check_mark:  |
| math/big |  [:x:](#math/big)  |
| math/bits |  :heavy_check_mark:  |
| math/cmplx |  :heavy_check_mark:  |
| math/rand |  [:x:](#math/rand)  |
| mime |  [:x:](#mime)  |
| mime/multipart |  [:x:](#mime/multipart)  |
| mime/quotedprintable |  :heavy_check_mark:  |
| net |  [:x:](#net)  |
| net/http |  [:x:](#net/http)  |
| net/http/cgi |  [:x:](#net/http/cgi)  |
| net/http/cookiejar |  [:x:](#net/http/cookiejar)  |
| net/http/fcgi |  [:x:](#net/http/fcgi)  |
| net/http/httptest |  [:x:](#net/http/httptest)  |
| net/http/httptrace |  [:x:](#net/http/httptrace)  |
| net/http/httputil |  [:x:](#net/http/httputil)  |
| net/http/pprof |  [:x:](#net/http/pprof)  |
| net/mail |  [:x:](#net/mail)  |
| net/rpc |  [:x:](#net/rpc)  |
| net/rpc/jsonrpc |  [:x:](#net/rpc/jsonrpc)  |
| net/smtp |  [:x:](#net/smtp)  |
| net/textproto |  [:x:](#net/textproto)  |
| net/url |  :heavy_check_mark:  |
| os |  :heavy_check_mark:  |
| os/exec |  [:x:](#os/exec)  |
| os/signal |  [:x:](#os/signal)  |
| os/user |  [:x:](#os/user)  |
| path |  :heavy_check_mark:  |
| path/filepath |  :heavy_check_mark:  |
| plugin |  :heavy_check_mark:  |
| reflect |  :heavy_check_mark:  |
| regexp |  :heavy_check_mark:  |
| regexp/syntax |  :heavy_check_mark:  |
| runtime |  :heavy_check_mark:  |
| runtime/cgo |  :heavy_check_mark:  |
| runtime/debug |  [:x:](#runtime/debug)  |
| runtime/msan |  [:x:](#runtime/msan)  |
| runtime/pprof |  [:x:](#runtime/pprof)  |
| runtime/race |  :heavy_check_mark:  |
| runtime/trace |  [:x:](#runtime/trace)  |
| sort |  :heavy_check_mark:  |
| strconv |  :heavy_check_mark:  |
| strings |  :heavy_check_mark:  |
| sync |  :heavy_check_mark:  |
| sync/atomic |  :heavy_check_mark:  |
| syscall |  :heavy_check_mark:  |
| syscall/js |  :heavy_check_mark:  |
| testing |  [:x:](#testing)  |
| testing/iotest |  :heavy_check_mark:  |
| testing/quick |  [:x:](#testing/quick)  |
| text/scanner |  [:x:](#text/scanner)  |
| text/tabwriter |  :heavy_check_mark:  |
| text/template |  [:x:](#text/template)  |
| text/template/parse |  [:x:](#text/template/parse)  |
| time |  :heavy_check_mark:  |
| unicode |  :heavy_check_mark:  |
| unicode/utf16 |  :heavy_check_mark:  |
| unicode/utf8 |  :heavy_check_mark:  |
| unsafe |  :heavy_check_mark:  |



## archive/tar
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/archive_tar:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/archive/tar/common.go:445:15: DeepEqual not declared by package reflect
error: couldn't load packages due to errors: archive/tar
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## archive/zip
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/archive_zip:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/archive/zip/register.go:106:21: Map not declared by package sync
/usr/local/go/src/archive/zip/register.go:107:21: Map not declared by package sync
error: couldn't load packages due to errors: archive/zip
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## bufio
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/bufio:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## bytes
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/bytes:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## compress/bzip2
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/compress_bzip2:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## compress/flate
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/compress_flate:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: compress/flate.generateFixedOffsetEncoding
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## compress/gzip
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/compress_gzip:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: compress/flate.generateFixedOffsetEncoding
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## compress/lzw
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/compress_lzw:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## compress/zlib
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/compress_zlib:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: compress/flate.generateFixedOffsetEncoding
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## container
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/container:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/go/src/github.com/trashhalo/tinygo-import-report/main.go:5:4: could not import container (invalid package name: "")
error: couldn't load packages due to errors: github.com/trashhalo/tinygo-import-report
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## container/heap
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/container_heap:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## container/list
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/container_list:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## container/ring
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/container_ring:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## context
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/context:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
error: couldn't load packages due to errors: context
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: init: slice expression with bounds
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto/aes
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_aes:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## crypto/cipher
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_cipher:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## crypto/des
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_des:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## crypto/dsa
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_dsa:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: math/rand.NewSource
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto/ecdsa
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_ecdsa:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
error: couldn't load packages due to errors: encoding/asn1
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto/elliptic
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_elliptic:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: math/rand.NewSource
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto/hmac
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_hmac:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## crypto/md5
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_md5:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: init: slice expression with bounds
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto/rand
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_rand:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: math/rand.NewSource
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto/rc4
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_rc4:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## crypto/rsa
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_rsa:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: init: slice expression with bounds
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto/sha1
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_sha1:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: init: slice expression with bounds
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto/sha256
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_sha256:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: init: slice expression with bounds
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto/sha512
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_sha512:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: init: slice expression with bounds
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto/subtle
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_subtle:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## crypto/tls
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_tls:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
error: couldn't load packages due to errors: internal/singleflight, vendor/golang_org/x/crypto/cryptobyte, encoding/asn1 and 2 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## crypto/x509/pkix
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/crypto_x509_pkix:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
error: couldn't load packages due to errors: encoding/asn1
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## database/sql
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/database_sql:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/database/sql/driver/types.go:227:20: invalid operation: rv.Type().Elem() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/database/sql/sql.go:537:7: Locker not declared by package sync
/usr/local/go/src/database/sql/sql.go:3051:7: Locker not declared by package sync
/usr/local/go/src/database/sql/sql.go:3073:23: Locker not declared by package sync
/usr/local/go/src/database/sql/sql.go:3069:29: Stack not declared by package runtime
/usr/local/go/src/database/sql/sql.go:3062:5: invalid operation: dr (variable of type driverResult) has no field or method Lock
/usr/local/go/src/database/sql/sql.go:3063:11: invalid operation: dr (variable of type driverResult) has no field or method Unlock
/usr/local/go/src/database/sql/sql.go:3056:5: invalid operation: dr (variable of type driverResult) has no field or method Lock
/usr/local/go/src/database/sql/sql.go:3057:11: invalid operation: dr (variable of type driverResult) has no field or method Unlock
/usr/local/go/src/database/sql/sql.go:2505:5: invalid operation: ds (variable of type *driverStmt) has no field or method Lock
/usr/local/go/src/database/sql/sql.go:2506:11: invalid operation: ds (variable of type *driverStmt) has no field or method Unlock
/usr/local/go/src/database/sql/sql.go:2334:5: invalid operation: ds (variable of type *driverStmt) has no field or method Lock
/usr/local/go/src/database/sql/sql.go:2335:11: invalid operation: ds (variable of type *driverStmt) has no field or method Unlock
/usr/local/go/src/database/sql/sql.go:2642:22: invalid operation: rs.closemu (variable of type sync.RWMutex) has no field or method RLocker
/usr/local/go/src/database/sql/convert.go:500:20: invalid operation: rv.Type().Elem() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/database/sql/convert.go:357:31: invalid operation: sv.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/database/sql/convert.go:367:41: invalid operation: sv.Type() (value of type reflect.Type) has no field or method ConvertibleTo
/usr/local/go/src/database/sql/convert.go:368:13: invalid operation: sv (variable of type reflect.Value) has no field or method Convert
/usr/local/go/src/database/sql/convert.go:380:19: Zero not declared by package reflect
/usr/local/go/src/database/sql/convert.go:383:18: New not declared by package reflect
/usr/local/go/src/database/sql/sql.go:546:5: invalid operation: ds (variable of type *driverStmt) has no field or method Lock
/usr/local/go/src/database/sql/sql.go:547:11: invalid operation: ds (variable of type *driverStmt) has no field or method Unlock
error: couldn't load packages due to errors: context, database/sql/driver, database/sql
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## database/sql/driver
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/database_sql_driver:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/database/sql/driver/types.go:227:20: invalid operation: rv.Type().Elem() (value of type reflect.Type) has no field or method Implements
error: couldn't load packages due to errors: context, database/sql/driver
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## encoding
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## encoding/ascii85
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding_ascii85:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## encoding/asn1
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding_asn1:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
error: couldn't load packages due to errors: encoding/asn1
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## encoding/base32
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding_base32:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: encoding/base32.NewEncoding
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## encoding/base64
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding_base64:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: encoding/base64.NewEncoding
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## encoding/binary
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding_binary:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## encoding/csv
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding_csv:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## encoding/gob
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding_gob:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/encoding/gob/type.go:39:24: Map not declared by package sync
/usr/local/go/src/encoding/gob/type.go:801:26: Map not declared by package sync
/usr/local/go/src/encoding/gob/type.go:802:26: Map not declared by package sync
/usr/local/go/src/encoding/gob/type.go:844:8: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:866:8: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:867:9: invalid operation: rt (variable of type reflect.Type) has no field or method PkgPath
/usr/local/go/src/encoding/gob/type.go:868:21: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:870:21: invalid operation: rt (variable of type reflect.Type) has no field or method PkgPath
/usr/local/go/src/encoding/gob/type.go:870:42: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:715:28: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:722:31: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:496:34: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/type.go:514:37: invalid operation: t.Elem() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:531:17: invalid operation: typ (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:119:12: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/encoding/gob/type.go:126:9: invalid operation: rt (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/gob/type.go:142:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/gob/encode.go:643:70: invalid operation: f (variable of type reflect.StructField) has no field or method Index
/usr/local/go/src/encoding/gob/encode.go:603:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/gob/encode.go:562:34: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/encoder.go:127:29: invalid operation: st (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/encode.go:320:18: invalid operation: value (variable of type reflect.Value) has no field or method FieldByIndex
/usr/local/go/src/encoding/gob/decode.go:1258:17: New not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:376:11: invalid operation: value (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/gob/decode.go:233:18: New not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:1202:17: invalid operation: base (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/decode.go:1118:30: invalid operation: srt (variable of type reflect.Type) has no field or method FieldByName
/usr/local/go/src/encoding/gob/decode.go:1019:31: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:948:22: PtrTo not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:825:35: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:656:21: Zero not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:625:11: invalid operation: value (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/gob/decode.go:562:21: MakeMapWithSize not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:564:19: invalid operation: mtyp (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:568:18: New not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:568:27: invalid operation: mtyp (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:569:18: Zero not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:569:28: invalid operation: mtyp (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:570:19: New not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:571:19: Zero not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:575:9: invalid operation: value (variable of type reflect.Value) has no field or method SetMapIndex
/usr/local/go/src/encoding/gob/decode.go:466:18: invalid operation: value (variable of type reflect.Value) has no field or method FieldByIndex
error: couldn't load packages due to errors: encoding/gob
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## encoding/hex
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding_hex:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## encoding/json
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding_json:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/encoding/json/encode.go:345:23: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1249:21: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1102:24: invalid operation: sf (variable of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/json/encode.go:1103:11: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1118:15: invalid operation: sf (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/json/encode.go:1131:11: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/encode.go:1150:26: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1176:51: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/encode.go:749:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:698:11: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:703:9: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:391:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:395:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:400:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:404:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:364:11: WaitGroup not declared by package sync
/usr/local/go/src/encoding/json/decode.go:459:41: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/decode.go:483:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:485:15: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:913:18: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:934:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:963:6: invalid operation: v (variable of type reflect.Value) has no field or method SetBytes
/usr/local/go/src/encoding/json/decode.go:967:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1001:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1009:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/encoding/json/decode.go:1017:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/encoding/json/decode.go:1025:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowFloat
/usr/local/go/src/encoding/json/decode.go:634:40: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:652:12: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:657:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:657:24: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:664:18: MakeMap not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:704:23: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:706:25: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:741:25: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:748:38: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/decode.go:789:19: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:793:31: invalid operation: reflect.ValueOf(key) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:794:17: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:31: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:805:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:809:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:813:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:817:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:822:6: invalid operation: v (variable of type reflect.Value) has no field or method SetMapIndex
/usr/local/go/src/encoding/json/decode.go:526:8: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:557:14: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:17: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:27: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:563:13: Copy not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:567:7: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/json/decode.go:599:17: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:604:6: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/json/decode.go:160:15: cannot convert nil (untyped nil value) to reflect.Type
error: couldn't load packages due to errors: encoding/json
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## encoding/pem
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding_pem:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: encoding/base64.NewEncoding
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## encoding/xml
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/encoding_xml:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/encoding/xml/typeinfo.go:47:19: Map not declared by package sync
/usr/local/go/src/encoding/xml/typeinfo.go:318:14: invalid operation: typ (variable of type reflect.Type) has no field or method FieldByIndex
/usr/local/go/src/encoding/xml/typeinfo.go:319:14: invalid operation: typ (variable of type reflect.Type) has no field or method FieldByIndex
/usr/local/go/src/encoding/xml/typeinfo.go:114:29: invalid operation: f (variable of type *reflect.StructField) has no field or method Index
/usr/local/go/src/encoding/xml/typeinfo.go:117:11: invalid operation: f (variable of type *reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/xml/typeinfo.go:168:20: invalid operation: f (variable of type *reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/xml/typeinfo.go:175:19: invalid operation: f (variable of type *reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/xml/typeinfo.go:63:10: invalid operation: f (variable of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/xml/typeinfo.go:63:30: invalid operation: f (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/xml/typeinfo.go:63:46: invalid operation: f (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/xml/typeinfo.go:68:9: invalid operation: f (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/xml/read.go:602:20: New not declared by package reflect
/usr/local/go/src/encoding/xml/read.go:660:7: invalid operation: dst (variable of type reflect.Value) has no field or method SetBytes
/usr/local/go/src/encoding/xml/read.go:188:7: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/xml/read.go:329:20: New not declared by package reflect
/usr/local/go/src/encoding/xml/read.go:334:38: invalid operation: val.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/read.go:342:37: invalid operation: pv.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/read.go:347:38: invalid operation: val.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/read.go:353:37: invalid operation: pv.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/read.go:393:17: Append not declared by package reflect
/usr/local/go/src/encoding/xml/read.go:393:37: Zero not declared by package reflect
/usr/local/go/src/encoding/xml/read.go:397:6: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/xml/read.go:557:70: invalid operation: saveData.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/read.go:566:37: invalid operation: pv.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/read.go:244:20: New not declared by package reflect
/usr/local/go/src/encoding/xml/read.go:248:38: invalid operation: val.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/read.go:255:37: invalid operation: pv.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/read.go:261:38: invalid operation: val.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/read.go:268:37: invalid operation: pv.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/read.go:277:19: Append not declared by package reflect
/usr/local/go/src/encoding/xml/read.go:277:39: Zero not declared by package reflect
/usr/local/go/src/encoding/xml/read.go:281:8: invalid operation: val (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/xml/marshal.go:638:16: invalid operation: typ (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/xml/marshal.go:639:26: invalid operation: typ (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/xml/marshal.go:643:33: invalid operation: typ.Elem() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/xml/marshal.go:813:38: invalid operation: vf.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/marshal.go:825:39: invalid operation: pv.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/marshal.go:766:12: Copy not declared by package reflect
/usr/local/go/src/encoding/xml/marshal.go:544:38: invalid operation: val.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/marshal.go:557:37: invalid operation: pv.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/marshal.go:569:38: invalid operation: val.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/marshal.go:580:37: invalid operation: pv.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/marshal.go:427:31: invalid operation: typ (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/marshal.go:432:37: invalid operation: pv.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/marshal.go:438:31: invalid operation: typ (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/marshal.go:443:37: invalid operation: pv.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/xml/marshal.go:486:15: invalid operation: typ (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/xml/typeinfo.go:356:20: New not declared by package reflect
error: couldn't load packages due to errors: encoding/xml
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## errors
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/errors:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## expvar
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/expvar:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/encoding/json/encode.go:345:23: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1249:21: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1102:24: invalid operation: sf (variable of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/json/encode.go:1103:11: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1118:15: invalid operation: sf (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/json/encode.go:1131:11: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/encode.go:1150:26: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1176:51: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/encode.go:749:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:698:11: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:703:9: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:391:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:395:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:400:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:404:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:364:11: WaitGroup not declared by package sync
/usr/local/go/src/encoding/json/decode.go:459:41: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/decode.go:483:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:485:15: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
/usr/local/go/src/encoding/json/decode.go:913:18: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:934:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:963:6: invalid operation: v (variable of type reflect.Value) has no field or method SetBytes
/usr/local/go/src/encoding/json/decode.go:967:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1001:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1009:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/encoding/json/decode.go:1017:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/encoding/json/decode.go:1025:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowFloat
/usr/local/go/src/encoding/json/decode.go:634:40: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:652:12: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:657:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:657:24: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:664:18: MakeMap not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:704:23: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:706:25: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:741:25: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:748:38: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/decode.go:789:19: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:793:31: invalid operation: reflect.ValueOf(key) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:794:17: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:31: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:805:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:809:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:813:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:817:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:822:6: invalid operation: v (variable of type reflect.Value) has no field or method SetMapIndex
/usr/local/go/src/encoding/json/decode.go:526:8: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:557:14: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:17: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:27: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:563:13: Copy not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:567:7: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/json/decode.go:599:17: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:604:6: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/json/decode.go:160:15: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/net/http/httptrace/trace.go:202:22: MakeFunc not declared by package reflect
/usr/local/go/src/net/http/httptrace/trace.go:203:11: invalid operation: tfCopy (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/httptrace/trace.go:204:14: invalid operation: of (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/h2_bundle.go:3690:16: Cond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:6804:24: Cond not declared by package sync
/usr/local/go/src/net/http/server.go:646:16: Cond not declared by package sync
/usr/local/go/src/net/http/transport.go:2016:38: Locker not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:3137:17: Stack not declared by package runtime
/usr/local/go/src/net/http/h2_bundle.go:5870:24: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:1746:23: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:655:18: NewCond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:7223:17: NewCond not declared by package sync
/usr/local/go/src/expvar/expvar.go:102:14: Map not declared by package sync
/usr/local/go/src/expvar/expvar.go:251:17: Map not declared by package sync
/usr/local/go/src/expvar/expvar.go:341:23: MemStats not declared by package runtime
/usr/local/go/src/expvar/expvar.go:342:10: ReadMemStats not declared by package runtime
error: couldn't load packages due to errors: context, expvar, net/http and 7 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## flag
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/flag:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/flag/flag.go:410:15: New not declared by package reflect
/usr/local/go/src/flag/flag.go:412:15: Zero not declared by package reflect
error: couldn't load packages due to errors: flag
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## fmt
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/fmt:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## hash
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/hash:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## hash/adler32
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/hash_adler32:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## hash/crc32
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/hash_crc32:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: hash/crc32.simpleMakeTable
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## hash/crc64
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/hash_crc64:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: hash/crc64.makeTable
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## hash/fnv
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/hash_fnv:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## html
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/html:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: strings.NewReplacer
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## html/template
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/html_template:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/encoding/json/encode.go:345:23: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1249:21: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1102:24: invalid operation: sf (variable of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/json/encode.go:1103:11: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1118:15: invalid operation: sf (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/text/template/parse/parse.go:196:26: Error not declared by package runtime
/usr/local/go/src/encoding/json/encode.go:1131:11: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/encode.go:1150:26: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1176:51: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/encode.go:749:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:698:11: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:703:9: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:391:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:395:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:400:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:404:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:364:11: WaitGroup not declared by package sync
/usr/local/go/src/encoding/json/decode.go:459:41: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/decode.go:483:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:485:15: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:913:18: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:934:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:963:6: invalid operation: v (variable of type reflect.Value) has no field or method SetBytes
/usr/local/go/src/encoding/json/decode.go:967:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1001:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1009:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/encoding/json/decode.go:1017:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/encoding/json/decode.go:1025:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowFloat
/usr/local/go/src/encoding/json/decode.go:634:40: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/text/template/funcs.go:140:19: Zero not declared by package reflect
/usr/local/go/src/text/template/funcs.go:142:18: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/funcs.go:145:70: invalid operation: value.Type() (value of type reflect.Type) has no field or method ConvertibleTo
/usr/local/go/src/text/template/funcs.go:146:17: invalid operation: value (variable of type reflect.Value) has no field or method Convert
/usr/local/go/src/text/template/funcs.go:93:11: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:95:11: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:95:32: invalid operation: typ (variable of type reflect.Type) has no field or method Out
/usr/local/go/src/encoding/json/decode.go:652:12: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/funcs.go:75:88: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumOut
/usr/local/go/src/encoding/json/decode.go:657:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:657:24: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:664:18: MakeMap not declared by package reflect
/usr/local/go/src/text/template/funcs.go:196:45: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/funcs.go:203:17: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:704:23: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:706:25: Zero not declared by package reflect
/usr/local/go/src/text/template/funcs.go:248:92: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:250:15: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/funcs.go:252:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/funcs.go:256:17: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/funcs.go:267:11: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/encoding/json/decode.go:741:25: New not declared by package reflect
/usr/local/go/src/text/template/funcs.go:268:18: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/funcs.go:278:14: invalid operation: v (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/encoding/json/decode.go:748:38: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/text/template/exec.go:949:15: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/text/template/exec.go:949:50: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/text/template/exec.go:950:30: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:789:19: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/exec.go:950:79: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:793:31: invalid operation: reflect.ValueOf(key) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:794:17: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:31: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:805:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:809:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:813:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:817:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:822:6: invalid operation: v (variable of type reflect.Value) has no field or method SetMapIndex
/usr/local/go/src/text/template/exec.go:159:16: Error not declared by package runtime
/usr/local/go/src/encoding/json/decode.go:526:8: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:557:14: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:17: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:27: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:563:13: Copy not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:567:7: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/json/decode.go:599:17: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:604:6: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/text/template/exec.go:866:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:856:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:845:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:834:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:823:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:812:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:769:19: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:160:15: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:793:10: invalid operation: typ (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/text/template/exec.go:722:13: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:728:19: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:735:12: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:735:33: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:738:20: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:748:59: invalid operation: value.Type().Elem() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:753:16: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:653:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:654:18: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:656:79: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:658:25: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:659:69: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:663:71: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/exec.go:670:32: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:673:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:674:18: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:674:25: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:681:12: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:681:19: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:682:10: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:686:13: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:695:16: invalid operation: fun (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/text/template/exec.go:584:19: invalid operation: ptr (variable of type reflect.Value) has no field or method MethodByName
/usr/local/go/src/text/template/exec.go:591:33: invalid operation: receiver.Type() (value of type reflect.Type) has no field or method FieldByName
/usr/local/go/src/text/template/exec.go:596:22: invalid operation: receiver (variable of type reflect.Value) has no field or method FieldByIndex
/usr/local/go/src/text/template/exec.go:612:21: invalid operation: nameVal.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:612:50: invalid operation: receiver.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/exec.go:622:23: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:529:25: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:431:56: invalid operation: value.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/text/template/exec.go:375:20: invalid operation: val (variable of type reflect.Value) has no field or method Recv
/usr/local/go/src/html/template/js.go:135:16: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/html/template/content.go:143:16: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/html/template/content.go:143:57: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
error: couldn't load packages due to errors: html/template, encoding/json, text/template and 1 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## image
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/image:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
Basic Block in function 'github.com/trashhalo/tinygo-import-report.init' does not have terminator!
label %entry
error: Basic Block in function 'github.com/trashhalo/tinygo-import-report.init' does not have terminator!
label %entry

Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## image/color
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/image_color:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## image/color/palette
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/image_color_palette:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
Basic Block in function 'github.com/trashhalo/tinygo-import-report.init' does not have terminator!
label %entry
error: Basic Block in function 'github.com/trashhalo/tinygo-import-report.init' does not have terminator!
label %entry

Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## image/draw
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/image_draw:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
Basic Block in function 'github.com/trashhalo/tinygo-import-report.init' does not have terminator!
label %entry
error: Basic Block in function 'github.com/trashhalo/tinygo-import-report.init' does not have terminator!
label %entry

Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## image/gif
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/image_gif:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
Basic Block in function 'github.com/trashhalo/tinygo-import-report.init' does not have terminator!
label %entry
Both operands to a binary operator are not of the same type!
  %slice.cap = sub i32 1024, i8 %37, !dbg !8447
Call parameter type does not match function signature!
  %37 = load i8, i8* %36, !dbg !8446
 i32  call void @runtime.sliceBoundsCheck(i32 1024, i8 %37, i8 %35), !dbg !8447
Invalid InsertValueInst operands!
  %39 = insertvalue { i8*, i32, i32 } %38, i8 %slice.len, 1, !dbg !8447
Both operands to a binary operator are not of the same type!
  %slice.len = sub i8 %45, i32 0, !dbg !8541
Call parameter type does not match function signature!
  %45 = load i8, i8* %44, !dbg !8540
 i32  call void @runtime.sliceBoundsCheck(i32 1024, i32 0, i8 %45), !dbg !8541
Invalid InsertValueInst operands!
  %47 = insertvalue { i8*, i32, i32 } %46, i8 %slice.len, 1, !dbg !8541
Both operands to a binary operator are not of the same type!
  %slice.len = sub i8 %6, i32 0, !dbg !8822
Call parameter type does not match function signature!
  %6 = extractvalue { i8, %runtime._interface } %5, 0, !dbg !8816
 i32  call void @runtime.sliceBoundsCheck(i32 1024, i32 0, i8 %6), !dbg !8822
Invalid InsertValueInst operands!
  %18 = insertvalue { i8*, i32, i32 } %17, i8 %slice.len, 1, !dbg !8822
error: Basic Block in function 'github.com/trashhalo/tinygo-import-report.init' does not have terminator!
label %entry
Both operands to a binary operator are not of the same type!
  %slice.cap = sub i32 1024, i8 %37, !dbg !8447
Call parameter type does not match function signature!
  %37 = load i8, i8* %36, !dbg !8446
 i32  call void @runtime.sliceBoundsCheck(i32 1024, i8 %37, i8 %35), !dbg !8447
Invalid InsertValueInst operands!
  %39 = insertvalue { i8*, i32, i32 } %38, i8 %slice.len, 1, !dbg !8447
Both operands to a binary operator are not of the same type!
  %slice.len = sub i8 %45, i32 0, !dbg !8541
Call parameter type does not match function signature!
  %45 = load i8, i8* %44, !dbg !8540
 i32  call void @runtime.sliceBoundsCheck(i32 1024, i32 0, i8 %45), !dbg !8541
Invalid InsertValueInst operands!
  %47 = insertvalue { i8*, i32, i32 } %46, i8 %slice.len, 1, !dbg !8541
Both operands to a binary operator are not of the same type!
  %slice.len = sub i8 %6, i32 0, !dbg !8822
Call parameter type does not match function signature!
  %6 = extractvalue { i8, %runtime._interface } %5, 0, !dbg !8816
 i32  call void @runtime.sliceBoundsCheck(i32 1024, i32 0, i8 %6), !dbg !8822
Invalid InsertValueInst operands!
  %18 = insertvalue { i8*, i32, i32 } %17, i8 %slice.len, 1, !dbg !8822

Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## image/jpeg
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/image_jpeg:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: full slice expressions (with max): []byte
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## image/png
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/image_png:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: compress/flate.generateFixedOffsetEncoding
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## index/suffixarray
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/index_suffixarray:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## io
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/io:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## io/ioutil
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/io_ioutil:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## log
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/log:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## log/syslog
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/log_syslog:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
error: couldn't load packages due to errors: context, net, internal/singleflight
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## math
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/math:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## math/big
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/math_big:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: math/rand.NewSource
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## math/bits
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/math_bits:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## math/cmplx
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/math_cmplx:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## math/rand
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/math_rand:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init call: math/rand.NewSource
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## mime
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/mime:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
error: couldn't load packages due to errors: mime
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## mime/multipart
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/mime_multipart:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
error: couldn't load packages due to errors: context, mime, net and 1 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## mime/quotedprintable
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/mime_quotedprintable:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## net
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
error: couldn't load packages due to errors: context, net, internal/singleflight
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/http
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_http:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/net/http/httptrace/trace.go:202:22: MakeFunc not declared by package reflect
/usr/local/go/src/net/http/httptrace/trace.go:203:11: invalid operation: tfCopy (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/httptrace/trace.go:204:14: invalid operation: of (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/h2_bundle.go:3690:16: Cond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:6804:24: Cond not declared by package sync
/usr/local/go/src/net/http/server.go:646:16: Cond not declared by package sync
/usr/local/go/src/net/http/transport.go:2016:38: Locker not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:3137:17: Stack not declared by package runtime
/usr/local/go/src/net/http/h2_bundle.go:5870:24: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:1746:23: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:655:18: NewCond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:7223:17: NewCond not declared by package sync
error: couldn't load packages due to errors: net, vendor/golang_org/x/crypto/cryptobyte, encoding/asn1 and 5 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/http/cgi
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_http_cgi:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/net/http/httptrace/trace.go:202:22: MakeFunc not declared by package reflect
/usr/local/go/src/net/http/httptrace/trace.go:203:11: invalid operation: tfCopy (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/httptrace/trace.go:204:14: invalid operation: of (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/h2_bundle.go:3690:16: Cond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:6804:24: Cond not declared by package sync
/usr/local/go/src/net/http/server.go:646:16: Cond not declared by package sync
/usr/local/go/src/net/http/transport.go:2016:38: Locker not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:3137:17: Stack not declared by package runtime
/usr/local/go/src/net/http/h2_bundle.go:5870:24: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:1746:23: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:655:18: NewCond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:7223:17: NewCond not declared by package sync
error: couldn't load packages due to errors: net/http/httptrace, encoding/asn1, net/http and 5 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/http/cookiejar
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_http_cookiejar:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/net/http/httptrace/trace.go:202:22: MakeFunc not declared by package reflect
/usr/local/go/src/net/http/httptrace/trace.go:203:11: invalid operation: tfCopy (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/httptrace/trace.go:204:14: invalid operation: of (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/h2_bundle.go:3690:16: Cond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:6804:24: Cond not declared by package sync
/usr/local/go/src/net/http/server.go:646:16: Cond not declared by package sync
/usr/local/go/src/net/http/transport.go:2016:38: Locker not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:3137:17: Stack not declared by package runtime
/usr/local/go/src/net/http/h2_bundle.go:5870:24: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:1746:23: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:655:18: NewCond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:7223:17: NewCond not declared by package sync
error: couldn't load packages due to errors: net, mime, encoding/asn1 and 5 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/http/fcgi
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_http_fcgi:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/net/http/httptrace/trace.go:202:22: MakeFunc not declared by package reflect
/usr/local/go/src/net/http/httptrace/trace.go:203:11: invalid operation: tfCopy (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/httptrace/trace.go:204:14: invalid operation: of (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/h2_bundle.go:3690:16: Cond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:6804:24: Cond not declared by package sync
/usr/local/go/src/net/http/server.go:646:16: Cond not declared by package sync
/usr/local/go/src/net/http/transport.go:2016:38: Locker not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:3137:17: Stack not declared by package runtime
/usr/local/go/src/net/http/h2_bundle.go:5870:24: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:1746:23: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:655:18: NewCond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:7223:17: NewCond not declared by package sync
error: couldn't load packages due to errors: vendor/golang_org/x/crypto/cryptobyte, encoding/asn1, context and 5 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/http/httptest
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_http_httptest:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
/usr/local/go/src/flag/flag.go:410:15: New not declared by package reflect
/usr/local/go/src/flag/flag.go:412:15: Zero not declared by package reflect
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/net/http/httptrace/trace.go:202:22: MakeFunc not declared by package reflect
/usr/local/go/src/net/http/httptrace/trace.go:203:11: invalid operation: tfCopy (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/httptrace/trace.go:204:14: invalid operation: of (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/h2_bundle.go:3690:16: Cond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:6804:24: Cond not declared by package sync
/usr/local/go/src/net/http/server.go:646:16: Cond not declared by package sync
/usr/local/go/src/net/http/transport.go:2016:38: Locker not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:3137:17: Stack not declared by package runtime
/usr/local/go/src/net/http/h2_bundle.go:5870:24: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:1746:23: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:655:18: NewCond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:7223:17: NewCond not declared by package sync
/usr/local/go/src/net/http/httptest/server.go:44:10: WaitGroup not declared by package sync
error: couldn't load packages due to errors: mime, flag, encoding/asn1 and 7 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/http/httptrace
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_http_httptrace:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/net/http/httptrace/trace.go:202:22: MakeFunc not declared by package reflect
/usr/local/go/src/net/http/httptrace/trace.go:203:11: invalid operation: tfCopy (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/httptrace/trace.go:204:14: invalid operation: of (variable of type reflect.Value) has no field or method Call
error: couldn't load packages due to errors: internal/singleflight, vendor/golang_org/x/crypto/cryptobyte, context and 3 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/http/httputil
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_http_httputil:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/net/http/httptrace/trace.go:202:22: MakeFunc not declared by package reflect
/usr/local/go/src/net/http/httptrace/trace.go:203:11: invalid operation: tfCopy (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/httptrace/trace.go:204:14: invalid operation: of (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/h2_bundle.go:3690:16: Cond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:6804:24: Cond not declared by package sync
/usr/local/go/src/net/http/server.go:646:16: Cond not declared by package sync
/usr/local/go/src/net/http/transport.go:2016:38: Locker not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:3137:17: Stack not declared by package runtime
/usr/local/go/src/net/http/h2_bundle.go:5870:24: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:1746:23: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:655:18: NewCond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:7223:17: NewCond not declared by package sync
error: couldn't load packages due to errors: vendor/golang_org/x/crypto/cryptobyte, encoding/asn1, net and 5 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/http/pprof
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_http_pprof:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/runtime/trace/trace.go:147:10: StopTrace not declared by package runtime
/usr/local/go/src/runtime/trace/trace.go:124:20: StartTrace not declared by package runtime
/usr/local/go/src/runtime/trace/trace.go:129:20: ReadTrace not declared by package runtime
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:345:23: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1249:21: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1102:24: invalid operation: sf (variable of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/json/encode.go:1103:11: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1118:15: invalid operation: sf (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/json/encode.go:1131:11: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/encode.go:1150:26: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1176:51: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/encode.go:749:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:698:11: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:703:9: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:391:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:395:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:400:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:404:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:364:11: WaitGroup not declared by package sync
/usr/local/go/src/encoding/json/decode.go:459:41: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/decode.go:483:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:485:15: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:913:18: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:934:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:963:6: invalid operation: v (variable of type reflect.Value) has no field or method SetBytes
/usr/local/go/src/encoding/json/decode.go:967:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1001:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1009:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/encoding/json/decode.go:1017:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/encoding/json/decode.go:1025:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowFloat
/usr/local/go/src/encoding/json/decode.go:634:40: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/runtime/pprof/pprof.go:372:135: BlockProfileRecord not declared by package runtime
/usr/local/go/src/encoding/json/decode.go:652:12: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/runtime/pprof/pprof.go:693:84: StackRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:718:31: StackRecord not declared by package runtime
/usr/local/go/src/encoding/json/decode.go:657:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:657:24: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:664:18: MakeMap not declared by package reflect
/usr/local/go/src/runtime/pprof/protomem.go:15:46: MemProfileRecord not declared by package runtime
/usr/local/go/src/encoding/json/decode.go:704:23: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:706:25: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:741:25: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:748:38: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/decode.go:789:19: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:793:31: invalid operation: reflect.ValueOf(key) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:794:17: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:31: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:805:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:809:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:813:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:817:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:822:6: invalid operation: v (variable of type reflect.Value) has no field or method SetMapIndex
/usr/local/go/src/runtime/pprof/proto.go:223:20: CallersFrames not declared by package runtime
/usr/local/go/src/encoding/json/decode.go:526:8: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:557:14: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:17: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:27: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:563:13: Copy not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:567:7: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/json/decode.go:599:17: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:604:6: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/runtime/pprof/pprof.go:920:20: SetMutexProfileFraction not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:807:10: SetCPUProfileRate not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:762:10: SetCPUProfileRate not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:700:18: StackRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:706:22: StackRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:678:16: Stack not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:542:24: MemStats not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:546:26: MemStats not declared by package runtime
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/runtime/pprof/pprof.go:547:11: ReadMemStats not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:556:18: MemProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:557:19: MemProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:562:22: MemProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:563:19: MemProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:572:45: MemProfileRate not declared by package runtime
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/runtime/pprof/pprof.go:581:20: MemProfileRecord not declared by package runtime
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:160:15: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/text/template/parse/parse.go:196:26: Error not declared by package runtime
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/runtime/pprof/pprof.go:596:13: MemProfileRate not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:490:20: CallersFrames not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:877:18: BlockProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:878:19: MutexProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:880:22: BlockProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:881:19: MutexProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:900:49: SetMutexProfileFraction not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:819:18: MutexProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:825:18: BlockProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:826:19: BlockProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:828:22: BlockProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:829:19: BlockProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:813:18: BlockProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:526:18: MemProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:656:63: ThreadCreateProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:650:18: ThreadCreateProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:669:60: GoroutineProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:661:17: NumGoroutine not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:287:15: Callers not declared by package runtime
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/text/template/funcs.go:140:19: Zero not declared by package reflect
/usr/local/go/src/text/template/funcs.go:142:18: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/funcs.go:145:70: invalid operation: value.Type() (value of type reflect.Type) has no field or method ConvertibleTo
/usr/local/go/src/text/template/funcs.go:146:17: invalid operation: value (variable of type reflect.Value) has no field or method Convert
/usr/local/go/src/text/template/funcs.go:93:11: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:95:11: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:95:32: invalid operation: typ (variable of type reflect.Type) has no field or method Out
/usr/local/go/src/text/template/funcs.go:75:88: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:196:45: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/funcs.go:203:17: Zero not declared by package reflect
/usr/local/go/src/text/template/funcs.go:248:92: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:250:15: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/funcs.go:252:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/funcs.go:256:17: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/funcs.go:267:11: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/funcs.go:268:18: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/funcs.go:278:14: invalid operation: v (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/text/template/exec.go:949:15: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/text/template/exec.go:949:50: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/text/template/exec.go:950:30: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:950:79: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:159:16: Error not declared by package runtime
/usr/local/go/src/text/template/exec.go:866:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:856:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:845:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:834:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:823:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:812:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:769:19: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:793:10: invalid operation: typ (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/text/template/exec.go:722:13: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:728:19: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:735:12: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:735:33: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:738:20: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:748:59: invalid operation: value.Type().Elem() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:753:16: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:653:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:654:18: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:656:79: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:658:25: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:659:69: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:663:71: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/exec.go:670:32: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:673:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:674:18: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:674:25: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:681:12: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:681:19: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:682:10: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:686:13: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:695:16: invalid operation: fun (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/text/template/exec.go:584:19: invalid operation: ptr (variable of type reflect.Value) has no field or method MethodByName
/usr/local/go/src/text/template/exec.go:591:33: invalid operation: receiver.Type() (value of type reflect.Type) has no field or method FieldByName
/usr/local/go/src/text/template/exec.go:596:22: invalid operation: receiver (variable of type reflect.Value) has no field or method FieldByIndex
/usr/local/go/src/text/template/exec.go:612:21: invalid operation: nameVal.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:612:50: invalid operation: receiver.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/exec.go:622:23: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:529:25: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:431:56: invalid operation: value.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/text/template/exec.go:375:20: invalid operation: val (variable of type reflect.Value) has no field or method Recv
/usr/local/go/src/html/template/js.go:135:16: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/html/template/content.go:143:16: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/html/template/content.go:143:57: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/net/http/httptrace/trace.go:202:22: MakeFunc not declared by package reflect
/usr/local/go/src/net/http/httptrace/trace.go:203:11: invalid operation: tfCopy (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/httptrace/trace.go:204:14: invalid operation: of (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/h2_bundle.go:3690:16: Cond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:6804:24: Cond not declared by package sync
/usr/local/go/src/net/http/server.go:646:16: Cond not declared by package sync
/usr/local/go/src/net/http/transport.go:2016:38: Locker not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:3137:17: Stack not declared by package runtime
/usr/local/go/src/net/http/h2_bundle.go:5870:24: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:1746:23: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:655:18: NewCond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:7223:17: NewCond not declared by package sync
error: couldn't load packages due to errors: text/template/parse, text/template, encoding/asn1 and 11 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/mail
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_mail:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
error: couldn't load packages due to errors: context, internal/singleflight, mime and 1 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/rpc
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_rpc:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:345:23: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1249:21: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1102:24: invalid operation: sf (variable of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/json/encode.go:1103:11: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1118:15: invalid operation: sf (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/json/encode.go:1131:11: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/encode.go:1150:26: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1176:51: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/text/template/parse/parse.go:196:26: Error not declared by package runtime
/usr/local/go/src/encoding/json/encode.go:749:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:698:11: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:703:9: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:391:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:395:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:400:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:404:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:364:11: WaitGroup not declared by package sync
/usr/local/go/src/encoding/json/decode.go:459:41: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/decode.go:483:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:485:15: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:913:18: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:934:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:963:6: invalid operation: v (variable of type reflect.Value) has no field or method SetBytes
/usr/local/go/src/encoding/json/decode.go:967:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1001:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1009:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/encoding/json/decode.go:1017:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/encoding/json/decode.go:1025:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowFloat
/usr/local/go/src/encoding/json/decode.go:634:40: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:652:12: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:657:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:657:24: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:664:18: MakeMap not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:704:23: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:706:25: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:741:25: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:748:38: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/decode.go:789:19: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:793:31: invalid operation: reflect.ValueOf(key) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:794:17: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:31: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:805:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:809:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:813:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:817:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:822:6: invalid operation: v (variable of type reflect.Value) has no field or method SetMapIndex
/usr/local/go/src/encoding/json/decode.go:526:8: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:557:14: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:17: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:27: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:563:13: Copy not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:567:7: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/json/decode.go:599:17: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:604:6: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/json/decode.go:160:15: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/encoding/gob/type.go:39:24: Map not declared by package sync
/usr/local/go/src/encoding/gob/type.go:801:26: Map not declared by package sync
/usr/local/go/src/encoding/gob/type.go:802:26: Map not declared by package sync
/usr/local/go/src/encoding/gob/type.go:844:8: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:866:8: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:867:9: invalid operation: rt (variable of type reflect.Type) has no field or method PkgPath
/usr/local/go/src/encoding/gob/type.go:868:21: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:870:21: invalid operation: rt (variable of type reflect.Type) has no field or method PkgPath
/usr/local/go/src/encoding/gob/type.go:870:42: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:715:28: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:722:31: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:496:34: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/type.go:514:37: invalid operation: t.Elem() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:531:17: invalid operation: typ (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:119:12: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/encoding/gob/type.go:126:9: invalid operation: rt (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/gob/type.go:142:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/gob/encode.go:643:70: invalid operation: f (variable of type reflect.StructField) has no field or method Index
/usr/local/go/src/encoding/gob/encode.go:603:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/gob/encode.go:562:34: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/funcs.go:140:19: Zero not declared by package reflect
/usr/local/go/src/text/template/funcs.go:142:18: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/funcs.go:145:70: invalid operation: value.Type() (value of type reflect.Type) has no field or method ConvertibleTo
/usr/local/go/src/text/template/funcs.go:146:17: invalid operation: value (variable of type reflect.Value) has no field or method Convert
/usr/local/go/src/text/template/funcs.go:93:11: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:95:11: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:95:32: invalid operation: typ (variable of type reflect.Type) has no field or method Out
/usr/local/go/src/text/template/funcs.go:75:88: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:196:45: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/funcs.go:203:17: Zero not declared by package reflect
/usr/local/go/src/text/template/funcs.go:248:92: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:250:15: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/funcs.go:252:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/funcs.go:256:17: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/funcs.go:267:11: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/funcs.go:268:18: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/funcs.go:278:14: invalid operation: v (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/encoding/gob/encoder.go:127:29: invalid operation: st (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/exec.go:949:15: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/text/template/exec.go:949:50: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/text/template/exec.go:950:30: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:950:79: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:159:16: Error not declared by package runtime
/usr/local/go/src/text/template/exec.go:866:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:856:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:845:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:834:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:823:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:812:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:769:19: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:793:10: invalid operation: typ (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/text/template/exec.go:722:13: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:728:19: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:735:12: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/encoding/gob/encode.go:320:18: invalid operation: value (variable of type reflect.Value) has no field or method FieldByIndex
/usr/local/go/src/encoding/gob/decode.go:1258:17: New not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:376:11: invalid operation: value (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/gob/decode.go:233:18: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:735:33: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:738:20: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:748:59: invalid operation: value.Type().Elem() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:753:16: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:653:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:654:18: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:656:79: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:658:25: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:659:69: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:663:71: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/exec.go:670:32: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:673:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:674:18: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:674:25: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:681:12: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:681:19: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:682:10: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:686:13: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:695:16: invalid operation: fun (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/text/template/exec.go:584:19: invalid operation: ptr (variable of type reflect.Value) has no field or method MethodByName
/usr/local/go/src/text/template/exec.go:591:33: invalid operation: receiver.Type() (value of type reflect.Type) has no field or method FieldByName
/usr/local/go/src/text/template/exec.go:596:22: invalid operation: receiver (variable of type reflect.Value) has no field or method FieldByIndex
/usr/local/go/src/text/template/exec.go:612:21: invalid operation: nameVal.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:612:50: invalid operation: receiver.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/exec.go:622:23: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:529:25: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:431:56: invalid operation: value.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/text/template/exec.go:375:20: invalid operation: val (variable of type reflect.Value) has no field or method Recv
/usr/local/go/src/encoding/gob/decode.go:1202:17: invalid operation: base (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/decode.go:1118:30: invalid operation: srt (variable of type reflect.Type) has no field or method FieldByName
/usr/local/go/src/encoding/gob/decode.go:1019:31: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:948:22: PtrTo not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:825:35: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:656:21: Zero not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:625:11: invalid operation: value (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/gob/decode.go:562:21: MakeMapWithSize not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:564:19: invalid operation: mtyp (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:568:18: New not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:568:27: invalid operation: mtyp (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:569:18: Zero not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:569:28: invalid operation: mtyp (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:570:19: New not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:571:19: Zero not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:575:9: invalid operation: value (variable of type reflect.Value) has no field or method SetMapIndex
/usr/local/go/src/encoding/gob/decode.go:466:18: invalid operation: value (variable of type reflect.Value) has no field or method FieldByIndex
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/html/template/js.go:135:16: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/html/template/content.go:143:16: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/html/template/content.go:143:57: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/net/http/httptrace/trace.go:202:22: MakeFunc not declared by package reflect
/usr/local/go/src/net/http/httptrace/trace.go:203:11: invalid operation: tfCopy (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/httptrace/trace.go:204:14: invalid operation: of (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/h2_bundle.go:3690:16: Cond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:6804:24: Cond not declared by package sync
/usr/local/go/src/net/http/server.go:646:16: Cond not declared by package sync
/usr/local/go/src/net/http/transport.go:2016:38: Locker not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:3137:17: Stack not declared by package runtime
/usr/local/go/src/net/http/h2_bundle.go:5870:24: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:1746:23: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:655:18: NewCond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:7223:17: NewCond not declared by package sync
/usr/local/go/src/net/rpc/server.go:156:21: Method not declared by package reflect
/usr/local/go/src/net/rpc/server.go:190:18: Map not declared by package sync
/usr/local/go/src/net/rpc/server.go:375:70: WaitGroup not declared by package sync
/usr/local/go/src/net/rpc/server.go:288:22: invalid operation: typ (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/net/rpc/server.go:289:17: invalid operation: typ (variable of type reflect.Type) has no field or method Method
/usr/local/go/src/net/rpc/server.go:218:22: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/net/rpc/server.go:218:35: invalid operation: t (variable of type reflect.Type) has no field or method PkgPath
/usr/local/go/src/net/rpc/server.go:563:18: New not declared by package reflect
/usr/local/go/src/net/rpc/server.go:565:18: New not declared by package reflect
/usr/local/go/src/net/rpc/server.go:576:19: New not declared by package reflect
/usr/local/go/src/net/rpc/server.go:580:29: MakeMap not declared by package reflect
/usr/local/go/src/net/rpc/server.go:463:17: WaitGroup not declared by package sync
/usr/local/go/src/net/rpc/server.go:245:43: invalid operation: reflect.Indirect(s.rcvr).Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/net/rpc/server.go:268:37: PtrTo not declared by package reflect
error: couldn't load packages due to errors: net, internal/singleflight, encoding/json and 11 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/rpc/jsonrpc
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_rpc_jsonrpc:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/mime/type.go:15:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:16:22: Map not declared by package sync
/usr/local/go/src/mime/type.go:21:20: Map not declared by package sync
/usr/local/go/src/mime/type.go:24:27: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:345:23: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1249:21: Map not declared by package sync
/usr/local/go/src/encoding/json/encode.go:1102:24: invalid operation: sf (variable of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/json/encode.go:1103:11: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1118:15: invalid operation: sf (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/json/encode.go:1131:11: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/encode.go:1150:26: invalid operation: sf (variable of type reflect.StructField) has no field or method Anonymous
/usr/local/go/src/encoding/json/encode.go:1176:51: invalid operation: ft (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:39:24: Map not declared by package sync
/usr/local/go/src/encoding/gob/type.go:801:26: Map not declared by package sync
/usr/local/go/src/encoding/gob/type.go:802:26: Map not declared by package sync
/usr/local/go/src/encoding/gob/type.go:844:8: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:866:8: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:867:9: invalid operation: rt (variable of type reflect.Type) has no field or method PkgPath
/usr/local/go/src/encoding/gob/type.go:868:21: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:870:21: invalid operation: rt (variable of type reflect.Type) has no field or method PkgPath
/usr/local/go/src/encoding/gob/type.go:870:42: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:715:28: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:722:31: invalid operation: rt (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:496:34: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/type.go:514:37: invalid operation: t.Elem() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:531:17: invalid operation: typ (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/type.go:119:12: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/encoding/gob/type.go:126:9: invalid operation: rt (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/gob/type.go:142:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/gob/encode.go:643:70: invalid operation: f (variable of type reflect.StructField) has no field or method Index
/usr/local/go/src/encoding/gob/encode.go:603:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/gob/encode.go:562:34: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/parse/parse.go:196:26: Error not declared by package runtime
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/encoding/json/encode.go:749:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:698:11: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:703:9: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/encode.go:391:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:395:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:400:7: invalid operation: t (variable of type reflect.Type) has no field or method Implements
/usr/local/go/src/encoding/json/encode.go:404:14: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/encode.go:364:11: WaitGroup not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/encoding/json/decode.go:459:41: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/json/decode.go:483:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:485:15: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:913:18: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:934:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:963:6: invalid operation: v (variable of type reflect.Value) has no field or method SetBytes
/usr/local/go/src/encoding/json/decode.go:967:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1001:9: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:1009:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/encoding/json/decode.go:1017:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/encoding/json/decode.go:1025:23: invalid operation: v (variable of type reflect.Value) has no field or method OverflowFloat
/usr/local/go/src/encoding/gob/encoder.go:127:29: invalid operation: st (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/encode.go:320:18: invalid operation: value (variable of type reflect.Value) has no field or method FieldByIndex
/usr/local/go/src/encoding/gob/decode.go:1258:17: New not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:376:11: invalid operation: value (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/gob/decode.go:233:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:634:40: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:652:12: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:657:16: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:657:24: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:664:18: MakeMap not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:704:23: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:706:25: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:741:25: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:748:38: invalid operation: v.Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/text/template/funcs.go:140:19: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:789:19: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/funcs.go:142:18: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/funcs.go:145:70: invalid operation: value.Type() (value of type reflect.Type) has no field or method ConvertibleTo
/usr/local/go/src/text/template/funcs.go:146:17: invalid operation: value (variable of type reflect.Value) has no field or method Convert
/usr/local/go/src/text/template/funcs.go:93:11: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:95:11: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:95:32: invalid operation: typ (variable of type reflect.Type) has no field or method Out
/usr/local/go/src/text/template/funcs.go:75:88: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:196:45: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/funcs.go:203:17: Zero not declared by package reflect
/usr/local/go/src/text/template/funcs.go:248:92: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:250:15: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/funcs.go:252:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/funcs.go:256:17: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/funcs.go:267:11: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/funcs.go:268:18: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/funcs.go:278:14: invalid operation: v (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/text/template/exec.go:949:15: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/text/template/exec.go:949:50: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/text/template/exec.go:950:30: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:950:79: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:159:16: Error not declared by package runtime
/usr/local/go/src/text/template/exec.go:866:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:856:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:845:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:834:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:823:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:812:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:769:19: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:793:10: invalid operation: typ (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/text/template/exec.go:722:13: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:728:19: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:735:12: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:735:33: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:738:20: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:748:59: invalid operation: value.Type().Elem() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:753:16: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:653:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:654:18: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:656:79: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:658:25: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:659:69: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:663:71: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/exec.go:670:32: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:673:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:674:18: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:674:25: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:681:12: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:681:19: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:682:10: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:686:13: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:695:16: invalid operation: fun (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/text/template/exec.go:584:19: invalid operation: ptr (variable of type reflect.Value) has no field or method MethodByName
/usr/local/go/src/text/template/exec.go:591:33: invalid operation: receiver.Type() (value of type reflect.Type) has no field or method FieldByName
/usr/local/go/src/text/template/exec.go:596:22: invalid operation: receiver (variable of type reflect.Value) has no field or method FieldByIndex
/usr/local/go/src/text/template/exec.go:612:21: invalid operation: nameVal.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:612:50: invalid operation: receiver.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/exec.go:622:23: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:529:25: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:431:56: invalid operation: value.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/gob/decode.go:1202:17: invalid operation: base (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/gob/decode.go:1118:30: invalid operation: srt (variable of type reflect.Type) has no field or method FieldByName
/usr/local/go/src/encoding/gob/decode.go:1019:31: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:948:22: PtrTo not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:825:35: invalid operation: t (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:656:21: Zero not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:625:11: invalid operation: value (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/gob/decode.go:562:21: MakeMapWithSize not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:564:19: invalid operation: mtyp (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:568:18: New not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:568:27: invalid operation: mtyp (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:569:18: Zero not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:569:28: invalid operation: mtyp (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/gob/decode.go:570:19: New not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:571:19: Zero not declared by package reflect
/usr/local/go/src/encoding/gob/decode.go:575:9: invalid operation: value (variable of type reflect.Value) has no field or method SetMapIndex
/usr/local/go/src/encoding/gob/decode.go:466:18: invalid operation: value (variable of type reflect.Value) has no field or method FieldByIndex
/usr/local/go/src/text/template/exec.go:375:20: invalid operation: val (variable of type reflect.Value) has no field or method Recv
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:793:31: invalid operation: reflect.ValueOf(key) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:794:17: PtrTo not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:18: New not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:795:31: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/encoding/json/decode.go:805:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:809:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:813:31: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:817:30: invalid operation: reflect.ValueOf(n) (value of type reflect.Value) has no field or method Convert
/usr/local/go/src/encoding/json/decode.go:822:6: invalid operation: v (variable of type reflect.Value) has no field or method SetMapIndex
/usr/local/go/src/encoding/json/decode.go:526:8: invalid operation: v (variable of type reflect.Value) has no field or method NumMethod
/usr/local/go/src/encoding/json/decode.go:557:14: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:17: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:558:27: invalid operation: v (variable of type reflect.Value) has no field or method Cap
/usr/local/go/src/encoding/json/decode.go:563:13: Copy not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:567:7: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/json/decode.go:599:17: Zero not declared by package reflect
/usr/local/go/src/encoding/json/decode.go:604:6: invalid operation: v (variable of type reflect.Value) has no field or method SetLen
/usr/local/go/src/encoding/json/decode.go:160:15: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
/usr/local/go/src/html/template/js.go:135:16: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/html/template/content.go:143:16: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/html/template/content.go:143:57: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/net/http/httptrace/trace.go:202:22: MakeFunc not declared by package reflect
/usr/local/go/src/net/http/httptrace/trace.go:203:11: invalid operation: tfCopy (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/httptrace/trace.go:204:14: invalid operation: of (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/net/http/h2_bundle.go:3690:16: Cond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:6804:24: Cond not declared by package sync
/usr/local/go/src/net/http/server.go:646:16: Cond not declared by package sync
/usr/local/go/src/net/http/transport.go:2016:38: Locker not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:3137:17: Stack not declared by package runtime
/usr/local/go/src/net/http/h2_bundle.go:5870:24: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:1746:23: Stack not declared by package runtime
/usr/local/go/src/net/http/server.go:655:18: NewCond not declared by package sync
/usr/local/go/src/net/http/h2_bundle.go:7223:17: NewCond not declared by package sync
/usr/local/go/src/net/rpc/server.go:156:21: Method not declared by package reflect
/usr/local/go/src/net/rpc/server.go:190:18: Map not declared by package sync
/usr/local/go/src/net/rpc/server.go:375:70: WaitGroup not declared by package sync
/usr/local/go/src/net/rpc/server.go:288:22: invalid operation: typ (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/net/rpc/server.go:289:17: invalid operation: typ (variable of type reflect.Type) has no field or method Method
/usr/local/go/src/net/rpc/server.go:218:22: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/net/rpc/server.go:218:35: invalid operation: t (variable of type reflect.Type) has no field or method PkgPath
/usr/local/go/src/net/rpc/server.go:563:18: New not declared by package reflect
/usr/local/go/src/net/rpc/server.go:565:18: New not declared by package reflect
/usr/local/go/src/net/rpc/server.go:576:19: New not declared by package reflect
/usr/local/go/src/net/rpc/server.go:580:29: MakeMap not declared by package reflect
/usr/local/go/src/net/rpc/server.go:463:17: WaitGroup not declared by package sync
/usr/local/go/src/net/rpc/server.go:245:43: invalid operation: reflect.Indirect(s.rcvr).Type() (value of type reflect.Type) has no field or method Name
/usr/local/go/src/net/rpc/server.go:268:37: PtrTo not declared by package reflect
error: couldn't load packages due to errors: internal/singleflight, html/template, net and 11 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/smtp
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_smtp:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
/usr/local/go/src/encoding/asn1/marshal.go:537:47: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/marshal.go:546:27: New not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:549:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:14: DeepEqual not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:558:47: Zero not declared by package reflect
/usr/local/go/src/encoding/asn1/marshal.go:447:18: invalid operation: t.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/marshal.go:479:89: invalid operation: t.Field(startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/marshal.go:483:99: invalid operation: t.Field(i + startingField) (value of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/common.go:174:26: invalid operation: t (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:658:80: invalid operation: ifaceType (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/encoding/asn1/asn1.go:810:115: invalid operation: fieldType (variable of type reflect.Type) has no field or method Name
/usr/local/go/src/encoding/asn1/asn1.go:831:12: Copy not declared by package reflect
/usr/local/go/src/encoding/asn1/asn1.go:901:27: invalid operation: structType.Field(i) (value of type reflect.StructField) has no field or method PkgPath
/usr/local/go/src/encoding/asn1/asn1.go:919:100: invalid operation: field (variable of type reflect.StructField) has no field or method Tag
/usr/local/go/src/encoding/asn1/asn1.go:932:12: Copy not declared by package reflect
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:266:58: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowInt
/usr/local/go/src/vendor/golang_org/x/crypto/cryptobyte/asn1.go:273:59: invalid operation: reflect.ValueOf(out).Elem() (value of type reflect.Value) has no field or method OverflowUint
error: couldn't load packages due to errors: context, net, encoding/asn1 and 2 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/textproto
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_textproto:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/internal/singleflight/singleflight.go:13:10: WaitGroup not declared by package sync
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/net/net_fake.go:178:17: Cond not declared by package sync
/usr/local/go/src/net/net_fake.go:179:17: Cond not declared by package sync
/usr/local/go/src/net/lookup.go:59:23: WaitGroup not declared by package sync
error: couldn't load packages due to errors: context, net, internal/singleflight
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## net/url
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/net_url:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## os
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/os:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## os/exec
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/os_exec:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
error: couldn't load packages due to errors: context
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## os/signal
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/os_signal:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: unknown expression: select nonblocking [t10<-sig]
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## os/user
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/os_user:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/os/user/lookup.go:53:9: undeclared name: lookupGroupId
/usr/local/go/src/os/user/lookup.go:47:9: undeclared name: lookupGroup
/usr/local/go/src/os/user/lookup.go:41:9: undeclared name: lookupUserId
/usr/local/go/src/os/user/lookup.go:32:9: undeclared name: lookupUser
/usr/local/go/src/os/user/lookup.go:11:41: undeclared name: current
/usr/local/go/src/os/user/lookup.go:58:9: undeclared name: listGroups
error: couldn't load packages due to errors: os/user
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## path
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/path:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## path/filepath
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/path_filepath:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## plugin
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/plugin:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## reflect
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/reflect:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## regexp
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/regexp:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## regexp/syntax
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/regexp_syntax:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## runtime
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/runtime:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## runtime/cgo
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/runtime_cgo:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## runtime/debug
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/runtime_debug:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/runtime/debug/stack.go:24:16: Stack not declared by package runtime
/usr/local/go/src/runtime/debug/garbage.go:37:34: MemStats not declared by package runtime
error: couldn't load packages due to errors: runtime/debug
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## runtime/msan
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/runtime_msan:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/go/src/github.com/trashhalo/tinygo-import-report/main.go:5:4: could not import runtime/msan (invalid package name: "")
error: couldn't load packages due to errors: github.com/trashhalo/tinygo-import-report
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## runtime/pprof
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/runtime_pprof:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/runtime/pprof/pprof.go:372:135: BlockProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:693:84: StackRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:718:31: StackRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/protomem.go:15:46: MemProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/proto.go:223:20: CallersFrames not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:920:20: SetMutexProfileFraction not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:807:10: SetCPUProfileRate not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:762:10: SetCPUProfileRate not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:700:18: StackRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:706:22: StackRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:678:16: Stack not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:542:24: MemStats not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:546:26: MemStats not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:547:11: ReadMemStats not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:556:18: MemProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:557:19: MemProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:562:22: MemProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:563:19: MemProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:572:45: MemProfileRate not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:581:20: MemProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:596:13: MemProfileRate not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:490:20: CallersFrames not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:877:18: BlockProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:878:19: MutexProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:880:22: BlockProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:881:19: MutexProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:900:49: SetMutexProfileFraction not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:819:18: MutexProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:825:18: BlockProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:826:19: BlockProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:828:22: BlockProfileRecord not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:829:19: BlockProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:813:18: BlockProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:526:18: MemProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:656:63: ThreadCreateProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:650:18: ThreadCreateProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:669:60: GoroutineProfile not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:661:17: NumGoroutine not declared by package runtime
/usr/local/go/src/runtime/pprof/pprof.go:287:15: Callers not declared by package runtime
error: couldn't load packages due to errors: context, runtime/pprof
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## runtime/race
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/runtime_race:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## runtime/trace
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/runtime_trace:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/runtime/trace/trace.go:147:10: StopTrace not declared by package runtime
/usr/local/go/src/runtime/trace/trace.go:124:20: StartTrace not declared by package runtime
/usr/local/go/src/runtime/trace/trace.go:129:20: ReadTrace not declared by package runtime
error: couldn't load packages due to errors: runtime/trace, context
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## sort
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/sort:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## strconv
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/strconv:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## strings
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/strings:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## sync
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/sync:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## sync/atomic
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/sync_atomic:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## syscall
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/syscall:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## syscall/js
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/syscall_js:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## testing
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/testing:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/runtime/debug/stack.go:24:16: Stack not declared by package runtime
/usr/local/go/src/runtime/debug/garbage.go:37:34: MemStats not declared by package runtime
/usr/local/go/src/context/context.go:472:26: invalid operation: reflect.TypeOf(key) (value of type reflect.Type) has no field or method Comparable
/usr/local/go/src/runtime/trace/trace.go:147:10: StopTrace not declared by package runtime
/usr/local/go/src/runtime/trace/trace.go:124:20: StartTrace not declared by package runtime
/usr/local/go/src/flag/flag.go:410:15: New not declared by package reflect
/usr/local/go/src/flag/flag.go:412:15: Zero not declared by package reflect
/usr/local/go/src/runtime/trace/trace.go:129:20: ReadTrace not declared by package runtime
/usr/local/go/src/testing/benchmark.go:26:22: MemStats not declared by package runtime
/usr/local/go/src/testing/testing.go:339:46: Frame not declared by package runtime
/usr/local/go/src/testing/testing.go:1136:11: MemProfileRate not declared by package runtime
/usr/local/go/src/testing/testing.go:1165:11: SetBlockProfileRate not declared by package runtime
/usr/local/go/src/testing/testing.go:1168:11: SetMutexProfileFraction not declared by package runtime
/usr/local/go/src/testing/testing.go:693:15: Callers not declared by package runtime
/usr/local/go/src/testing/testing.go:697:20: CallersFrames not declared by package runtime
/usr/local/go/src/testing/benchmark.go:616:14: WaitGroup not declared by package sync
/usr/local/go/src/testing/benchmark.go:493:15: Callers not declared by package runtime
/usr/local/go/src/testing/benchmark.go:101:11: ReadMemStats not declared by package runtime
/usr/local/go/src/testing/benchmark.go:90:11: ReadMemStats not declared by package runtime
/usr/local/go/src/testing/benchmark.go:76:11: ReadMemStats not declared by package runtime
/usr/local/go/src/testing/testing.go:660:10: Goexit not declared by package runtime
/usr/local/go/src/testing/testing.go:590:10: Goexit not declared by package runtime
/usr/local/go/src/testing/testing.go:351:15: Callers not declared by package runtime
/usr/local/go/src/testing/testing.go:355:20: CallersFrames not declared by package runtime
/usr/local/go/src/testing/testing.go:356:43: Frame not declared by package runtime
/usr/local/go/src/testing/testing.go:356:43: Frame not declared by package runtime
/usr/local/go/src/testing/testing.go:356:43: Frame not declared by package runtime
/usr/local/go/src/testing/testing.go:370:22: CallersFrames not declared by package runtime
/usr/local/go/src/testing/testing.go:849:15: Callers not declared by package runtime
/usr/local/go/src/testing/testing.go:882:11: Goexit not declared by package runtime
/usr/local/go/src/testing/allocs.go:27:23: MemStats not declared by package runtime
/usr/local/go/src/testing/allocs.go:28:10: ReadMemStats not declared by package runtime
/usr/local/go/src/testing/allocs.go:37:10: ReadMemStats not declared by package runtime
error: couldn't load packages due to errors: flag, context, runtime/trace and 2 more
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## testing/iotest
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/testing_iotest:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## testing/quick
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/testing_quick:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/flag/flag.go:410:15: New not declared by package reflect
/usr/local/go/src/flag/flag.go:412:15: Zero not declared by package reflect
/usr/local/go/src/testing/quick/quick.go:350:25: invalid operation: f (variable of type reflect.Type) has no field or method In
/usr/local/go/src/testing/quick/quick.go:352:95: invalid operation: f (variable of type reflect.Type) has no field or method In
/usr/local/go/src/testing/quick/quick.go:319:43: invalid operation: xType (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/testing/quick/quick.go:329:26: invalid operation: x (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/testing/quick/quick.go:330:26: invalid operation: y (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/testing/quick/quick.go:332:15: DeepEqual not declared by package reflect
/usr/local/go/src/testing/quick/quick.go:272:11: invalid operation: fType (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/testing/quick/quick.go:275:11: invalid operation: fType (variable of type reflect.Type) has no field or method Out
/usr/local/go/src/testing/quick/quick.go:279:43: invalid operation: fType (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/testing/quick/quick.go:289:12: invalid operation: fVal (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/testing/quick/quick.go:67:22: Zero not declared by package reflect
/usr/local/go/src/testing/quick/quick.go:71:15: New not declared by package reflect
/usr/local/go/src/testing/quick/quick.go:107:17: MakeMap not declared by package reflect
/usr/local/go/src/testing/quick/quick.go:109:36: invalid operation: concrete (variable of type reflect.Type) has no field or method Key
/usr/local/go/src/testing/quick/quick.go:118:18: Zero not declared by package reflect
/usr/local/go/src/testing/quick/quick.go:124:18: New not declared by package reflect
error: couldn't load packages due to errors: testing/quick, flag
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## text/scanner
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/text_scanner:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
error: todo: init: map key not implemented: rune
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## text/tabwriter
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/text_tabwriter:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## text/template
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/text_template:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/text/template/parse/parse.go:196:26: Error not declared by package runtime
/usr/local/go/src/text/template/funcs.go:140:19: Zero not declared by package reflect
/usr/local/go/src/text/template/funcs.go:142:18: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/funcs.go:145:70: invalid operation: value.Type() (value of type reflect.Type) has no field or method ConvertibleTo
/usr/local/go/src/text/template/funcs.go:146:17: invalid operation: value (variable of type reflect.Value) has no field or method Convert
/usr/local/go/src/text/template/funcs.go:93:11: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:95:11: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:95:32: invalid operation: typ (variable of type reflect.Type) has no field or method Out
/usr/local/go/src/text/template/funcs.go:75:88: invalid operation: v.Type() (value of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:196:45: invalid operation: v.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/funcs.go:203:17: Zero not declared by package reflect
/usr/local/go/src/text/template/funcs.go:248:92: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/funcs.go:250:15: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/funcs.go:252:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/funcs.go:256:17: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/funcs.go:267:11: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/funcs.go:268:18: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/funcs.go:278:14: invalid operation: v (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/text/template/exec.go:949:15: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/text/template/exec.go:949:50: invalid operation: v.Type() (value of type reflect.Type) has no field or method Implements
/usr/local/go/src/text/template/exec.go:950:30: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:950:79: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:159:16: Error not declared by package runtime
/usr/local/go/src/text/template/exec.go:866:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:856:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:845:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:834:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:823:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:812:20: New not declared by package reflect
/usr/local/go/src/text/template/exec.go:769:19: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:793:10: invalid operation: typ (variable of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/text/template/exec.go:722:13: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:728:19: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:735:12: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:735:33: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:738:20: invalid operation: value.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:748:59: invalid operation: value.Type().Elem() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:753:16: PtrTo not declared by package reflect
/usr/local/go/src/text/template/exec.go:653:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:654:18: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:656:79: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:658:25: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:659:69: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:663:71: invalid operation: typ (variable of type reflect.Type) has no field or method NumOut
/usr/local/go/src/text/template/exec.go:670:32: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:673:9: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:674:18: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:674:25: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:681:12: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:681:19: invalid operation: typ (variable of type reflect.Type) has no field or method NumIn
/usr/local/go/src/text/template/exec.go:682:10: invalid operation: typ (variable of type reflect.Type) has no field or method IsVariadic
/usr/local/go/src/text/template/exec.go:686:13: invalid operation: typ (variable of type reflect.Type) has no field or method In
/usr/local/go/src/text/template/exec.go:695:16: invalid operation: fun (variable of type reflect.Value) has no field or method Call
/usr/local/go/src/text/template/exec.go:584:19: invalid operation: ptr (variable of type reflect.Value) has no field or method MethodByName
/usr/local/go/src/text/template/exec.go:591:33: invalid operation: receiver.Type() (value of type reflect.Type) has no field or method FieldByName
/usr/local/go/src/text/template/exec.go:596:22: invalid operation: receiver (variable of type reflect.Value) has no field or method FieldByIndex
/usr/local/go/src/text/template/exec.go:612:21: invalid operation: nameVal.Type() (value of type reflect.Type) has no field or method AssignableTo
/usr/local/go/src/text/template/exec.go:612:50: invalid operation: receiver.Type() (value of type reflect.Type) has no field or method Key
/usr/local/go/src/text/template/exec.go:622:23: Zero not declared by package reflect
/usr/local/go/src/text/template/exec.go:529:25: cannot convert nil (untyped nil value) to reflect.Type
/usr/local/go/src/text/template/exec.go:431:56: invalid operation: value.Type() (value of type reflect.Type) has no field or method NumMethod
/usr/local/go/src/text/template/exec.go:375:20: invalid operation: val (variable of type reflect.Value) has no field or method Recv
error: couldn't load packages due to errors: text/template, text/template/parse
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## text/template/parse
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/text_template_parse:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report
/usr/local/go/src/text/template/parse/parse.go:196:26: Error not declared by package runtime
error: couldn't load packages due to errors: text/template/parse
Makefile:5: recipe for target 'build' failed
make: *** [build] Error 1

```


## time
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/time:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## unicode
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/unicode:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## unicode/utf16
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/unicode_utf16:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## unicode/utf8
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/unicode_utf8:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


## unsafe
```
docker run --rm -v /home/stephen/go/src/github.com/trashhalo/tinygo-import-report/tests/unsafe:/go/src/github.com/trashhalo/tinygo-import-report tinygo/tinygo \
build -o /go/src/github.com/trashhalo/tinygo-import-report/wasm.wasm -target wasm github.com/trashhalo/tinygo-import-report

```


