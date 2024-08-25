# Guesscheme

## 問題文
CVE-2024-5690をやってみてね！できるものならw🤯  
ref. [https://www.mozilla.org/en-US/security/advisories/mfsa2024-25/#CVE-2024-5690](https://www.mozilla.org/en-US/security/advisories/mfsa2024-25/#CVE-2024-5690)  

[http://34.42.244.226/](http://34.42.244.226/)  

**※ローカルでflagが取得できることを確認した後にリモートで試してください。**  

[guesscheme.zip](files/guesscheme.zip)  

## 難易度
**medium**  

## 作問にあたって
Firefoxの修正された0-dayを用いた問題です。  
2種類の手法で脆弱性が再現できるのですが、一方の手法のみAdvisoriesで公開されていました(いつか解説記事を出すかもしれません)。  
パッチを解析するなどして、JavaScriptが無効でも使える手法に気付けば解けます。  
ちなみに、Torのユーザトレースなどには利用できません。  

## 解法
Try Harder!  

## flag{guess_the_scheme_imgg}