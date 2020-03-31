# Discord kanalındaki veya DM'deki tüm mesajları silme

1. Buradaki bağlantıyı yeni sekmede açın ve kodu gösterdiğimiz yere yapıştırın : [deleteDiscordMessages.js](https://raw.githubusercontent.com/arvendf/DeleteDiscordMessages/master/deleteDiscordMessages.js)

2. Discord'u uygulama olarak değil internetten açınız (Örnek Chrome, Safari or Firefox)
açtıktan sonra sileceğiniz DM konuşmasına tıklayıp dediklerimizi uygulayın

3. Konsolu açmak için hangi tarayacıdan ne şekilde açacağınız :
    - Chrome (Windows, Linux, Chrome OS):
    <kbd>F12</kbd> or <kbd>CTRL</kbd>+<kbd>Shift</kbd>+<kbd>J</kbd> 
    - Chrome (Mac): 
    <kbd>Command</kbd>+<kbd>Option</kbd>+<kbd>J</kbd>
    - Safari (Mac): <kbd>Command</kbd>+<kbd>Option</kbd>+<kbd>C</kbd>
  
4. Kopyalamak için  (<kbd>Ctrl</kbd>+<kbd>V</kbd>) Consol'a kopyaladıktan sonra, <kbd>ENTER</kbd> tuşuna basmanız gerekmektedir, ve sonra sayfa açılacaktır;

5. Açıldıktan sonra ve mesajlarını sileceğiniz kişinin DM kutusundaysanız,log açıldıktan sonra mavi tuşlara basmanız gerekmektedir.
3.seçenek olan hedef yerinde önce ki mesaj ve sonra ki mesaj olarak adlandırdığımız yerlerde ilk seçenekte mesajı ve üstünü siler aşşağıda ki seçenekte mesaj ve aşşağı kısmını siler eğer orta bir yer belirlemek istiyorsanız iki mesajında ID'sini alıp çaprazlama bir şekilde seçtiğiniz yere kadar silinir. ( Ve unutmayalım bunlardan önce Developer yani yazılımcı kodcu modunu açmanız gerekmektedir.)

**TLDR:** Watch this [40s video instructions](https://imgur.com/a/vYmDNSZ)

<img src="https://arven.is-pretty.cool/5BiMRNw.png" height="600">

Bu yazılım sadece yardım amaçlı yapılmıştır ve sizler için yapılmıştır ❤️ ^^  , ⭐️ tuşuna basarak bize destek olabilirsiniz ve bu şekilde yazılımın daha fazla kullanıcıya ulaşmasını sağlarsınız.

If you have issues or just need help [open an issue here](https://github.com/victornpb/deleteDiscordMessages/issues)


----

#### Features

- Fastest script out there, it auto adjusts the delay to be the fastest your internet and discords allows!
- Easy interface with instructions
- Respect discord API rate limits
- Auto detect current [authToken](./help/authToken.md), [authorId](./help/authorId.md), [channelId](./help/channelId.md)
- It can delete a specific [range of messages](./help/messageId.md)
- It can delete only [links or attached files](./help/filters.md)
- Comprehensive log of messages being deleted (with their content)
- Hide private information for taking screenshots
- Detects system messages and skips them like "You started a voice call"
- You can use your computer and discord while it is running (unlike macro key scripts)
- Start/stop whenever you want
- Works with even thousands of messages

----

Originally from https://gist.github.com/victornpb/135f5b346dea4decfc8f63ad7d9cc182

----

#### About running code on your console

I don't recommend running code from random places you get on the internet. For that same reason, I deliberately choose to make it readable (that's why it is a bit lenthy). That way people can analyze it and understand what does it does before running it, and be sure that nothing sketchy is happening under the hood.

----
# DO NOT SHARE YOUR `authToken`!

Sharing your authToken on the internet will give full access to your account! [There are bots gathering credentials all over the internet](https://github.com/rndinfosecguy/Scavenger).
If you post your token by accident, LOGOUT from discord on that **same browser** you got that token imediately.
Changing your password will make sure that you get logged out of every device. I advice that you turn on [2FA](https://support.discordapp.com/hc/en-us/articles/219576828-Setting-up-Two-Factor-Authentication) afterwards.

If you are unsure do not share screenshots, or copy paste logs on the internet.

----
> **DISCLAIMER:**
> THE SOFTWARE AND ALL INFORMATION HERE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
>
> By using any code or information provided here you are agreeing to all parts of the above Disclaimer.
