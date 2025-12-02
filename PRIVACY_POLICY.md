# ПОЛИТИКА КОНФИДЕНЦИАЛЬНОСТИ
**Для программного обеспечения "A.B.P.O.P.A." (Aurora/Аврора)**  
*Версия 2.1 | Последнее обновление: 02.12.2025*

## 1. ОБЩИЕ ПОЛОЖЕНИЯ И ОПРЕДЕЛЕНИЯ
- 1.1. Настоящая Политика конфиденциальности (далее — "Политика") определяет порядок обработки и защиты информации, которая может быть получена от Пользователей (физических лиц) при использовании ими Discord-бота "A.B.P.O.P.A." (далее — "Бот"). Оператором обработки персональных данных выступает разработчик ashikito (ash1kito, sun †), далее — "Оператор".  

- 1.2. Политика разработана в соответствии с положениями Федерального закона от 27.07.2006 N 152-ФЗ "О персональных данных" (Российская Федерация), а также с учетом общих принципов Регламента (ЕС) 2016/679 (GDPR) в части, применимой к деятельности Оператора. Используя Бота, Пользователь дает информированное, конкретное и однозначное согласие на обработку своих данных в соответствии с настоящей Политикой.

## 2. СОСТАВ ОБРАБАТЫВАЕМЫХ ДАННЫХ И ЦЕЛИ ОБРАБОТКИ
- 2.1. Бот обрабатывает следующие категории технических данных, предоставляемых API платформы Discord исключительно в момент и для целей выполнения конкретной команды: а) Идентификаторы сервера (Guild ID) и канала (Channel ID) — для привязки настроек и конфигурации к конкретному сообществу; б) Идентификатор пользователя (User ID) — для реализации системы уровней доступа и ведения журнала аудита действий.  

- 2.2. Целью обработки указанных данных является исключительно обеспечение штатной функциональности Бота, включая управление правами доступа, персонализацию команд, отображение статуса сервера и логирование административных действий для поддержания целостности системы. Обработка данных не включает профилирование Пользователей или принятие автоматических решений, порождающих для них юридические последствия.

## 3. ПРИНЦИПЫ И СПОСОБЫ ОБРАБОТКИ ДАННЫХ
- 3.1. Все обрабатываемые данные хранятся локально в зашифрованной базе данных SQLite, развернутой на инфраструктуре, контролируемой Оператором. Для шифрования конфиденциальных полей применяется алгоритм AES-256-GCM. Передача данных третьим лицам для коммерческих или рекламных целей не осуществляется.  

- 3.2. Бот **не осуществляет** пассивного сбора, постоянного мониторинга или долгосрочного хранения содержимого сообщений (message content) в каналах Discord. Любой текст, предоставляемый Боту (например, через команду `/onemsg`), обрабатывается единовременно для выполнения запроса и не подлежит сохранению, если иное не заложено в логике конкретной команды, о чем Пользователь информируется отдельно.

## 4. ПРАВА СУБЪЕКТА ДАННЫХ И ХРАНЕНИЕ
- 4.1. Субъект персональных данных (Пользователь) имеет право на доступ к своим данным, их уточнение, блокирование или уничтожение, если обработка осуществляется с нарушением законодательства. Для реализации этих прав необходимо отправить запрос через систему Issues в репозитории проекта на GitHub, указав идентификатор своего аккаунта Discord (User ID) и сервера (Guild ID).  

- 4.2. Данные хранятся в течение срока, необходимого для достижения целей обработки, но не дольше, чем Бот является участником соответствующего сервера Discord. Удаление Бота с сервера является техническим сигналом для инициации процедуры полного удаления связанных с этим сервером данных из систем Оператора в разумные технические сроки.

## 5. ЗАКЛЮЧИТЕЛЬНЫЕ ПОЛОЖЕНИЯ
- 5.1. Оператор принимает технические и организационные меры для защиты обрабатываемых данных от неправомерного или случайного доступа, уничтожения, изменения или блокирования. В случае возникновения инцидента, затрагивающего безопасность данных, Оператор обязуется в разумные сроки уведомить администраторов затронутых серверов Discord через доступные публичные каналы связи.  

- 5.2. Оператор оставляет за собой право вносить изменения в настоящую Политику. Новая редакция вступает в силу с момента ее публикации в репозитории проекта на GitHub. При внесении существенных изменений, затрагивающих порядок обработки данных, будет размещено соответствующее уведомление в течение не менее 7 (семи) календарных дней до вступления изменений в силу.

*Для связи по вопросам, связанным с данными Условиями, используйте систему Issues в публичном репозитории проекта на GitHub (Или напишите мне в Discord по нику ashikito, а так же в Тех-Поддержку на [официальном канале](https://discord.gg/xSH9TBX7mc) Авроры).*

---

# PRIVACY POLICY
**For the software "A.B.P.O.P.A." (Aurora)**  
*Version 2.1 | Last updated: December 02, 2025*

## 1. GENERAL PROVISIONS AND DEFINITIONS
- 1.1. This Privacy Policy (hereinafter referred to as the "Policy") defines the procedure for processing and protecting information that may be obtained from Users (individuals) when using the Discord bot "A.B.P.O.P.A." (hereinafter referred to as the "Bot"). The operator of personal data processing is the developer ashikito (ash1kito, sun †), hereinafter referred to as the "Operator".

- 1.2. The Policy is developed in accordance with the provisions of the Federal Law No. 152-FZ of July 27, 2006 "On Personal Data" (Russian Federation), as well as taking into account the general principles of Regulation (EU) 2016/679 (GDPR) to the extent applicable to the Operator's activities. By using the Bot, the User provides informed, specific, and unambiguous consent to the processing of their data in accordance with this Policy.

## 2. SCOPE OF PROCESSED DATA AND PROCESSING PURPOSES
- 2.1. The Bot processes the following categories of technical data provided by the Discord platform API solely at the moment and for the purposes of executing a specific command: a) Server identifiers (Guild ID) and channel identifiers (Channel ID) — for binding settings and configuration to a specific community; b) User identifiers (User ID) — for implementing an access level system and maintaining an audit log of actions.

- 2.2. The purpose of processing the specified data is solely to ensure the standard functionality of the Bot, including managing access rights, personalizing commands, displaying server status, and logging administrative actions to maintain system integrity. Data processing does not include profiling Users or making automated decisions that produce legal effects concerning them.

## 3. PRINCIPLES AND METHODS OF DATA PROCESSING
- 3.1. All processed data is stored locally in an encrypted SQLite database deployed on infrastructure controlled by the Operator. The AES-256-GCM algorithm is used to encrypt confidential fields. Data is not transferred to third parties for commercial or advertising purposes.

- 2.2. The Bot **does not perform** passive collection, continuous monitoring, or long-term storage of message content in Discord channels. Any text provided to the Bot (e.g., via the `/onemsg` command) is processed once to fulfill the request and is not subject to retention, unless otherwise embedded in the logic of a specific command, about which the User is separately informed.

## 4. DATA SUBJECT RIGHTS AND STORAGE
- 4.1. The data subject (User) has the right to access their data, rectify, block, or delete it if the processing is carried out in violation of the law. To exercise these rights, it is necessary to send a request via the Issues system in the project repository on GitHub, specifying the Discord account identifier (User ID) and server identifier (Guild ID).

- 4.2. Data is stored for the period necessary to achieve the processing purposes, but no longer than the Bot remains a member of the relevant Discord server. The removal of the Bot from a server serves as a technical trigger to initiate the complete deletion of data associated with that server from the Operator's systems within reasonable technical timeframes.

## 5. FINAL PROVISIONS
- 5.1. The Operator takes technical and organizational measures to protect processed data from unauthorized or accidental access, destruction, alteration, or blocking. In the event of an incident affecting data security, the Operator undertakes to notify the administrators of the affected Discord servers via available public communication channels within a reasonable timeframe.

- 5.2. The Operator reserves the right to amend this Policy. The new version comes into force from the moment of its publication in the project repository on GitHub. In case of significant changes affecting the data processing procedure, a corresponding notice will be posted at least 7 (seven) calendar days before the changes take effect.

*For inquiries related to these Terms, use the Issues system in the public project repository on GitHub (or contact me on Discord via the username ashikito, as well as the Tech Support on the [official Aurora channel](https://discord.gg/xSH9TBX7mc)).*

---

*Note: This document is a translation of the original Privacy Policy in Russian. In case of any discrepancies, the original Russian version shall prevail.*
