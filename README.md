<h1 align="center">
    EurisLee's Repository
</h1>

<h3 align="center">
  <p align="center">
    <a href="https://github.com/eurislee/aur">Source</a> |
    <a href="https://github.com/eurislee/aur/issues">Feedback</a> |
    <a href="mailto:eurislee@gmail.com">Contact</a>
    <br><br>
  </p>
</h3>

## Add this repository

**Step 1.** Add the key.

Receive from key server.

```shell
sudo pacman-key --recv-keys 2B091B22784392C1
```

**Step 2.** It's recommended to verify the fingerprint.

```shell
sudo pacman-key --finger 2B091B22784392C1
```

**Step 3.** Locally sign the key.

```shell
sudo pacman-key --lsign-key 2B091B22784392C1
```

**Step 4.** Now in your `/etc/pacman.conf`, add this at the end of the file:

```dosini
[euris]
Server = https://aur.euris.me/$arch
```

**Step 5.** Refresh package databases.

```shell
sudo pacman -Syy
```

## Packages

| Name      | Architectures | Description                                                                                 |
|-----------|---------------|---------------------------------------------------------------------------------------------|
| `anydesk` | x86_64        | The Fast Remote Desktop Application                                                         |
