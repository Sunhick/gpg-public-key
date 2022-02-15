# gpg-public-key
Sunil's GPG Public keys

## Digital Proof
```
-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA512

Hello!

I'm Sunil Murthy with github alias sunhick, sunhick@gmail.com.

Here's my digital fingerprint -
       FE0F 6B71 2C06 7595 E7ED  20E7 F0B7 BA42 9658 890D

You can grab my public keys -
    gpg --keyserver keyserver.ubuntu.com --recv-key F0B7BA429658890D
-----BEGIN PGP SIGNATURE-----

iHUEARYKAB0WIQQZTLeTsJ8mvC+yZ7BGzgnKou2dRgUCYgsHGAAKCRBGzgnKou2d
RqvdAQDSefImw8dtWZDSpViD5ADqB1kFJV8e9A/UTkwA+w2pOgEAgjgnAVgNEZjT
A9xznc/FuGpxHhllRuzbwS77h7XamQQ=
=3kq3
-----END PGP SIGNATURE-----
```

## Keys
Grab my keys from ```keyserver.ubuntu.com``` by running -
```
$ gpg --keyserver keyserver.ubuntu.com --search-keys sunhick@gmail.com
$ $ gpg --keyserver keyserver.ubuntu.com --recv-keys F0B7BA429658890D
```

## Verify
```
$ curl -s https://raw.githubusercontent.com/Sunhick/gpg-public-key/main/signature.txt.asc | gpg --verify
```