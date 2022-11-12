## 1. vscode update notice 1.72

[Link Materi](https://programmingunama.readthedocs.io/id/latest/materi/vscode_1_72/)

## 2. Github Profile
[Github Profile Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)

## 3. How To Use Github on Public(Shared Computer) Safely

### A. Email

### B. Github SSH

[Official Documentations](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

[Tutorial Video](https://www.youtube.com/watch?v=8X4u9sca3Io&ab_channel=VictorGeislinger)

[Tutorial Video](https://www.youtube.com/watch?v=8X4u9sca3Io&ab_channel=VictorGeislinger)


1. Melihat SSH key yang tersimpan

```bash
ls -al ~/.ssh
```

2. Generate SSH-Key

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```

Masukan sesuai E-Mail yang dipakai di Github

3. Tekan Enter (Pilihan untuk directory SSH secara default /home/YOU/.ssh/)

```bash
> Enter a file in which to save the key (/home/YOU/.ssh/ALGORITHM):[Press enter]
```

4. Masukan Passphrase (Password Sebagai Pengamanan Tambahan)
   
```bash
> Enter passphrase (empty for no passphrase): [Type a passphrase]
> Enter same passphrase again: [Type passphrase again]
```

5. Menambahkan SSH-Key ke SSH-agent

memulai ssh-agent
```bash
eval "$(ssh-agent -s)"
```

menambahkan ssh key
```bash
ssh-add ~/.ssh/id_ed25519
```

6. Tambahkan SSH key ke github

[materi](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

Settings>SSH and GPG keys

7. Test SSH-Key
```bash
ssh -T git@github.com
```