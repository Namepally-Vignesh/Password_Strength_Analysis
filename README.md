# Password Strength Analysis

## **Objective**
- Evaluate password strength using online tools(online) and summarize best practices for creating secure passwords.

## **Steps i have done**  
1. Generated 5 passwords with varying complexity.  
2. Tested each password on strength-checking tools.
   Using online Websites, the site i have used;
     1. https://passwordmeter.com/
     2. https://www.security.org/how-secure-is-my-password/
4. Analyzed results of the Password.  
5. Researched common attacks like brute force, dictionary.  
6. Best practices of Creating/using passwords.

## **Passwords Tested**  
| Password                          | Strength Rating | Score (100)     | Notes                          |  
|-----------------------------------|-----------------|-----------------|--------------------------------|  
| `password123`                     | Very Weak       |       20        | Cracked instantly.             |  
| `P@ssw0rd!2023`                   | Moderate        |       65        | Predictable base.              |  
| `G7#kL9!qZ@x2\$wR`                | Very Strong     |       90        | Random, high entropy.          |  
| `3x@mpl3P@ssw0rd!#2023\$%^&*`     | Strong          |       95        | Long but contains fragments.   |  
| `BlueSky!Dancing@Moonlight#2023`  | Very Strong     |       85        | Memorable passphrase.          |  

## **Key Findings**  
- **Length > Complexity**: `G7#kL9!qZ@x2\$wR` (14 chars) outperformed `P@ssw0rd!2023` (10 chars).  
- **Passphrases Work**: `BlueSky!Dancing@Moonlight#2023` balances usability/security.  
- **Avoid**: Common words (`password`), sequential patterns (`123`).

## **best practices for creating strong passwords**
1. **Length:** Aim for passwords that are at least 12-16 characters long. Longer passwords are generally more secure.
2. **Character Variety:** Use a mix of uppercase letters, lowercase letters, numbers, and special characters (e.g., @, #, $, %, &, *).
   This increases the complexity of the password.
3. **Avoid Common Words:** Do not use easily guessable information such as common words, phrases, or personal details (e.g., birthdays, names).
4. **Use Passphrases:** Consider creating passphrases made up of random words or a memorable sentence. This can be easier to remember while still being secure.
5. **Randomness:** Use random combinations of characters rather than predictable patterns (e.g., "123456" or "password").
6. **Unique Passwords:** Use a different password for each account to prevent a single breach from compromising multiple accounts.
7. **Security Questions:** Choose security questions and answers that are not easily guessable or publicly available information.
8. **Two-Factor Authentication (2FA):** Enable 2FA wherever possible for an additional layer of security. This requires a second form of verification in addition to the password.
9. **Regular Updates:** Change passwords regularly and immediately update them if you suspect they may have been compromised.

## **Things learned from the evaluation**
1. **Prioritize Length:** Longer passwords are inherently more secure. Aim for at least 12-16 characters to increase resistance against attacks.
2. **Mix Character Types:** Incorporate a combination of uppercase letters, lowercase letters, numbers, and special characters to enhance complexity.
3. **Avoid Predictability:** Steer clear of common words, phrases, and easily guessable information (like birthdays or names) to reduce vulnerability.
4. **Consider Passphrases:** Use passphrases made up of random words or a memorable sentence. They can be easier to remember while still being strong.
5. **Unique Passwords for Each Account:** Never reuse passwords across different accounts. This limits the risk of multiple accounts being compromised if one password is breached.
6. **Utilize Password Managers:** Use password managers to generate and store complex passwords securely. This helps manage multiple passwords without the need to memorize each one.
7. **Regularly Update Passwords:** Change passwords periodically and immediately if you suspect they may have been compromised.
8. **Enable Two-Factor Authentication (2FA):** Whenever possible, enable 2FA for an added layer of security, requiring a second form of verification in addition to the password.
9. **Be Cautious with Security Questions:** Choose security questions that are not easily guessable or publicly available information to enhance account security.
10. **Test Password Strength:** Regularly test your passwords using online strength checkers to ensure they meet security standards and make adjustments as necessary.

## **Common Password Attacks**
1. **Brute Force Attack:**
- **Definition:** A method used by attackers to gain unauthorized access to accounts by systematically trying every possible combination of characters until the correct password is found.
- **How It Works:** Attackers use automated tools or scripts that can generate and test a vast number of password combinations in a short amount of time. The time required to crack a password depends on its length and complexity.
- **Time Complexity:** The time taken to crack a password increases exponentially with its length and the variety of characters used. For example, a 4-character password using only lowercase letters can be cracked quickly, while a 12-character password using a mix of uppercase, lowercase, numbers, and symbols can take years or even centuries to crack.
- **Mitigation:** To defend against brute force attacks, users should create long and complex passwords, implement account lockout mechanisms after a certain number of failed attempts, and use two-factor authentication (2FA).

2. **Dictionary Attacks:**
- **Definition:** A method where attackers use a precompiled list of common passwords, phrases, or words (the "dictionary") to guess the password.
- **How It Works:** Instead of trying every possible combination, attackers use a list of likely passwords, which may include common words, variations, and phrases. This method is faster than brute force attacks because it targets passwords that are more likely to be used by individuals.
- **Common Targets:** Dictionary attacks often target weak passwords, such as "password," "123456," or "qwerty," as well as variations of these (e.g., "Password1," "12345678").
- **Mitigation:** To protect against dictionary attacks, users should avoid using common words or phrases in their passwords. Instead, they should create unique, random, and complex passwords that do not appear in common password lists.

## **Impact of Password Complexity on Security**
**Increased Combinations:**
- Complex passwords that mix uppercase letters, lowercase letters, numbers, and special characters create many possible combinations, making them harder to crack through brute force attacks.

**Resistance to Common Attacks:**
- Complex passwords are less vulnerable to dictionary attacks, which use common words and phrases. Avoiding easily guessable information helps protect accounts.

**Length Matters:** 
- Longer passwords are generally more secure. Each extra character increases the time it takes for an attacker to crack the password, providing better defense.

**Mitigation of Guessing:** 
- Complex passwords are less likely to be guessed successfully. Simple or common passwords can be easily cracked, while complex ones require more effort to break.

**Enhanced Security Posture:** 
- Using complex passwords as part of a broader security strategy—like enabling two-factor authentication and regularly updating passwords—improves overall account security and reduces the risk of unauthorized access.
