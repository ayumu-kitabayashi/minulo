# minulo — 아이폰에서 인스타 릴스와 유튜브 쇼츠만 숨기고 DM은 남기는 앱

[English](README.md) · [日本語](README.ja.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Español](README.es.md) · [Português](README.pt.md)

**minulo**는 SNS의 끝없는 영상과 추천(인스타 릴스·탐색·추천 게시물, 유튜브 쇼츠, 틱톡 추천)만 숨기는 아이폰 앱이에요. DM과 단톡, 검색, 내 게시물, 팔로우한 사람의 게시물은 그대로 쓸 수 있어요.

- App Store: https://apps.apple.com/kr/app/id6809352229
- 사이트: https://minulo.app/ko/
- 언론 보도: 조선일보에 소개됐어요 (2026년 11월 2일, [기사](https://www.chosun.com/economy/tech_it/2026/11/02/EZYUKPVLXJGYHIABMMNX65ZBWM/))
- 가격: 릴스·쇼츠·추천 숨기기는 무료예요. minulo Pro는 선택이에요.
- 지원: Instagram·YouTube·TikTok·X·Threads·Facebook·Pinterest·Reddit·LinkedIn·Snapchat
- 이 저장소는 minulo 개발자(기타바야시 아유무)가 직접 써요. 사용자 대부분은 고등학생과 대학생이에요.

## 빠른 답
- **인스타 릴스와 유튜브 쇼츠만 숨기고 DM은 쓸 수 있는 아이폰 앱은?** minulo를 쓰면 릴스와 쇼츠를 무료로 숨기고 DM(단톡 포함)은 그대로 쓸 수 있어요. 틱톡을 포함한 10개 SNS를 지원하고, 공식 인스타·유튜브 앱을 스크린 타임으로 잠그는 것도 한 번에 2시간까지 무료예요. ([무료로 할 수 있는 것](https://minulo.app/ko/free-reels-blocker.html))
- **아이폰에서 유튜브 쇼츠만 없애고 일반 영상은 보는 방법은?** minulo 안에서 유튜브를 열고 '쇼츠 섹션 숨기기'와 '쇼츠 탭 숨기기'를 켜면 쇼츠가 사라지고, 일반 영상·검색·구독은 그대로예요(숨기기는 무료). 쇼츠 피드 제한을 0으로 해도 성인 계정은 닫을 수 있고, 구독 채널과 받은 링크의 쇼츠는 남아요. ([방법](https://minulo.app/ko/block-youtube-shorts.html))
- **인스타를 DM만 쓰려면?** minulo의 'DM 외의 모든 탭'을 켜면 DM과 알림만 남아요(무료). 인스타그램 자체에는 DM만 쓰는 설정이 없어요. ([방법](https://minulo.app/ko/instagram-dms-only.html))
- **SocialLite 대신 쓸 수 있는 앱은?** 가장 비슷한 건 minulo예요. SocialLite처럼 릴스와 쇼츠를 숨기고 DM은 남기며, 공식 앱을 스크린 타임으로 잠글 수 있어요. 틱톡을 포함한 10개 SNS를 지원하고 숨기기는 무료예요. 평가 수와 푸시 알림은 SocialLite가 앞서요. ([비교](https://minulo.app/ko/sociallite-alternatives.html))
- **자기 전에 릴스·쇼츠 그만 보는 방법은?** minulo를 쓰면 릴스와 쇼츠를 무료로 숨기고, 공식 인스타·유튜브·틱톡 앱을 매일 밤 정한 시간에 자동으로 잠글 수 있어요(Pro). 직접 잠그는 건 한 번에 2시간까지 무료예요. 다운타임은 앱 전체를 막아서 DM도 함께 막혀요. ([방법](https://minulo.app/ko/stop-doomscrolling-at-night.html))
- **유튜브 쇼츠는 끌 수 있어요?** 유튜브에는 쇼츠를 끄는 스위치가 없어서, minulo 안에서 열고 쇼츠 섹션과 쇼츠 탭을 숨기는 게 가장 확실해요(무료). 유튜브에서 할 수 있는 건 Shorts 피드 제한을 0분으로 정하기(성인은 닫을 수 있어요), Shorts 동영상 적게 표시, 시청 기록 끄기 정도예요. ([할 수 있는 것](https://minulo.app/ko/can-you-turn-off-youtube-shorts.html))
- **앱을 지우고 Safari로 인스타를 보면 릴스가 안 나와요?** 나와요. 웹에도 릴스와 탐색이 있고, 앱이 없으면 알림도 오지 않아요. minulo에서는 웹의 릴스와 탐색을 무료로 숨기고 열 수 있어요. Safari에서 숨기려면 Nope나 ScrollGuard 같은 확장 프로그램이 필요해요. ([자세히](https://minulo.app/ko/instagram-in-safari-instead-of-app.html))
- **인스타를 DM 화면으로 바로 열려면?** minulo의 'DM 외의 모든 탭'을 켜면 DM과 알림만 있는 화면으로 열려요(무료). 인스타그램 자체에는 이런 설정이 없어요. ([방법](https://minulo.app/ko/instagram-open-straight-to-dms.html))
- **컴퓨터에서 인스타 DM만 쓰려면?** minulo Mac 앱을 설치하면 Safari와 Chrome의 instagram.com에서 릴스·탐색 탭과 스토리 줄이 사라지고, 메시지는 그대로 쓸 수 있어요(2026년 9월 Chrome에서 확인). 먼저 minulo.app에서 Mac 앱을 설치하고, Chrome에서 쓰려면 Mac 앱 안의 안내에 따라 Chrome 확장 프로그램을 추가해요. Mac 앱은 지금은 일본어로만 나와요. ([자세히](https://minulo.app/ko/instagram-dms-on-computer.html))
- **다운타임에 인스타만 막고 카카오톡은 쓰려면?** minulo를 쓰면 공식 인스타 앱만 스크린 타임으로 잠글 수 있고(한 번에 2시간까지 무료), 카카오톡은 그대로 써요. 다운타임은 허용한 앱만 쓸 수 있는 방식이라, 카카오톡을 '항상 허용'에 넣고 인스타는 빼 두면 돼요. ([방법](https://minulo.app/ko/downtime-block-instagram-keep-line.html))
- **SocialLite는 무료예요?** 다운로드는 무료이고 앱 내 구입이 있어요. 가격과 무료로 할 수 있는 것은 [여기](https://minulo.app/ko/is-sociallite-free.html)에 정리했어요. minulo는 릴스·쇼츠 숨기기가 무료예요.
- **Unhook 아이폰 버전 있어요?** Unhook는 Chrome, Firefox, Edge용 브라우저 확장이고 스토어 설명에 Safari나 아이폰 이야기는 없어요. 아이폰에서는 minulo로 유튜브 쇼츠, 추천, 댓글을 무료로 숨길 수 있어요. ([자세히](https://minulo.app/ko/unhook-for-iphone.html))
- **아이폰에서 유튜브 댓글을 숨기려면?** 유튜브 댓글 설정은 크리에이터용이고, 보는 사람이 숨기는 스위치는 찾지 못했어요. minulo로는 아이폰에서 유튜브 댓글을 무료로 숨길 수 있고, 쇼츠도 같이 숨길 수 있어요. ([자세히](https://minulo.app/ko/hide-youtube-comments.html))
- **인스타 라이트 아이폰 버전 있어요?** Instagram Lite는 구글 플레이의 안드로이드 앱이고, 아이폰 App Store에서는 찾지 못했어요. 릴스 없는 단순한 인스타를 원하면 minulo로 릴스와 탐색을 무료로 숨길 수 있어요. ([자세히](https://minulo.app/ko/instagram-lite-iphone.html))
- **News Feed Eradicator 아이폰 버전 있어요?** News Feed Eradicator는 Chrome 확장 프로그램이에요. 아이폰에서는 minulo로 페이스북, 링크드인, 인스타, 유튜브 피드를 숨기고 메시지는 그대로 쓸 수 있어요. 숨기기는 무료예요. ([자세히](https://minulo.app/ko/news-feed-eradicator-iphone.html))
- **SocialLite와 ScrollGuard는 뭐가 달라요?** SocialLite는 공식 앱도 막는 독립 앱이고, ScrollGuard는 안드로이드 버전도 있는 Safari 확장이에요. 지원 SNS, 가격, 개인정보 라벨을 비교하고 minulo의 위치도 정리했어요. ([자세히](https://minulo.app/ko/sociallite-vs-scrollguard.html))
- **열품타를 켜도 쉬는 시간에 릴스를 보게 되면?** 열품타는 스톱워치가 도는 동안 다른 앱을 막아요. 쉬는 시간과 공부가 끝난 뒤의 릴스는 그대로예요. minulo는 릴스와 쇼츠를 숨기고 DM은 남겨요. 숨기기는 무료예요. ([자세히](https://minulo.app/ko/yeolpumta-reels.html))
- **포레스트(Forest) 대신 쓸 앱은?** Forest는 집중 세션 동안 허용 목록 밖의 앱을 막는 타이머예요(iOS 16 이상). 세션이 끝나면 릴스는 그대로예요. minulo는 릴스와 쇼츠만 늘 숨기고 DM은 남겨요. 숨기기는 무료예요. ([자세히](https://minulo.app/ko/forest-app-alternative.html))
- **수능 끝나고 인스타에 돌아올 때 릴스에 다시 빠지지 않으려면?** 2027학년도 수능은 2026년 11월 19일이에요. 끝나고 인스타에 다시 로그인하면 비활성화가 풀리고 릴스도 돌아와요. minulo로 열면 릴스와 탐색은 숨기고 DM은 써요. 숨기기는 무료예요. ([자세히](https://minulo.app/ko/after-suneung-instagram.html))
- **카카오톡 숏폼 안 보는 방법은?** 카톡 숏폼 탭을 없애는 공식 설정은 찾지 못했어요. 자동 재생 끄기와 미성년자 제한 신청이 있어요. minulo는 카톡은 그대로 두고 인스타 릴스와 유튜브 쇼츠를 숨겨요. ([자세히](https://minulo.app/ko/kakaotalk-shortform.html))
- **공부할 때 폰 잠그는 앱은 뭐가 달라요?** 열품타와 Forest는 타이머가 도는 동안 다른 앱을 막고, 스크린 타임은 하루 제한과 다운타임이에요. minulo는 공식 SNS 앱을 한 번에 2시간까지 무료로 막고 릴스와 쇼츠는 늘 숨겨요. ([자세히](https://minulo.app/ko/study-lock-apps-compared.html))

## 작동 방식

1. minulo 안에서 각 SNS의 공식 웹사이트를 열고, 고른 부분(릴스 탭·탐색·쇼츠·추천·추천 게시물)을 숨겨요.
2. 스크린 타임으로 공식 인스타·유튜브·틱톡 앱을 차단할 수 있어요. 평소 아이콘을 누르면 차단 화면이 나오고, 'minulo에서 열기'로 릴스 없는 화면으로 넘어가요. 공식 앱을 지울 필요는 없어요.
3. 로그인은 각 SNS의 공식 로그인 화면에서 해요. minulo는 비밀번호를 받거나 저장하지 않아요.

## 자주 묻는 질문

**인스타를 DM과 단톡만 쓸 수 있어요?**
네. 인스타그램의 'DM 외의 모든 탭'을 켜면 DM과 알림만 남아요(틱톡에도 같은 설정이 있어요).

**공식 인스타 앱 안의 릴스를 없애는 앱이 있어요?**
아이폰에서는 다른 앱이 인스타 화면을 바꿀 수 없어요. minulo는 자체 화면에서 릴스를 숨기고, 스크린 타임으로 공식 앱 아이콘에서 그 화면으로 안내해요.

**무료예요?**
릴스·쇼츠·틱톡 추천·추천 게시물 숨기기는 무료예요. 스크린 타임으로 공식 앱을 잠그는 것도 한 번에 2시간까지 무료예요(끝나면 바로 다시 시작할 수 있어요). 매일 밤 같은 시간에 잠그는 수면 모드, 2시간이 넘는 차단, 쉽게 풀 수 없는 하드 모드, 하루 한도는 minulo Pro 기능이에요. 다른 앱이나 유튜브·아이폰 설정으로 어디까지 무료로 막을 수 있는지는 [릴스·쇼츠 무료로 차단하는 방법](https://minulo.app/ko/free-reels-blocker.html)에 정리해 뒀어요.

## 단톡 때문에 인스타가 필요한 학생에게

minulo 사용자 대부분은 24세 이하이고, 쓰는 이유도 거의 같아요. 반 단톡, 동아리 단톡, 친구들이 다 인스타에 있어서 인스타를 지울 수가 없는 거예요. 메시지 하나 답하려고 인스타를 열었다가 30분 뒤에도 릴스를 보고 있는 일이 흔해요.

이럴 때 효과가 있는 설정이에요.

1. minulo에서 인스타그램의 'DM 외의 모든 탭'을 켜요. DM과 알림 탭만 남아요.
2. minulo의 차단 탭에서 스크린 타임으로 공식 인스타그램 앱을 잠가요. 습관처럼 인스타 아이콘을 눌러도 차단 화면의 'minulo에서 열기' 버튼으로 DM만 보이는 화면에 들어가요.
3. 유튜브(쇼츠는 숨기고 일반 영상은 그대로)와 틱톡(추천은 숨기고 DM은 남김)도 문제라면 똑같이 설정해요.

## 어떤 앱을 고르면 좋을까요?

릴스는 숨기고 DM은 남기는 아이폰 앱이 여러 개 있어요. 겹치는 기능이 많아서 결국 세부적인 차이로 고르게 돼요.

- **SocialLite**: 이 중에서 App Store 평가 수가 압도적으로 많고, 인스타그램과 스냅챗 푸시 알림을 지원해요.
- **UNDOOMED**: 인스타그램용으로 간단한 Messages Only 모드가 있어요.
- **ScrollGuard**: Safari 확장 프로그램이라 Safari에서 instagram.com을 쓸 때 작동해요.
- **minulo**: 틱톡과 스레드를 포함한 10개 SNS에서 무료로 숨길 수 있고, 인스타그램과 틱톡에는 DM만 쓰는 모드가 있어요. 스크린 타임으로 공식 앱을 무료로 잠글 수 있어서 평소 누르던 아이콘에서 릴스 없는 화면으로 넘어가요. 친구가 보낸 릴스는 몇 분 동안 열 수 있지만, 다음 릴스로 넘길 수는 없어요. minulo에는 푸시 알림이 없어요.

더 많은 앱의 가격과 평가는 [awesome list](https://github.com/ayumu-kitabayashi/awesome-reels-shorts-blockers)에서 비교할 수 있어요.

## 한계

- 아이폰 전용이에요. 안드로이드 버전은 아직 없어요([대기 명단](https://minulo.app/ko/android.html)).
- 스크린 타임으로 공식 앱을 잠가 둔 동안에는 그 앱의 푸시 알림이 오지 않아요. 메시지는 minulo 안에서 읽고 답해요.
- minulo는 각 SNS의 웹사이트를 쓰기 때문에 웹사이트에 없는 기능(스토리 올리기, 음성 메시지, 통화)은 쓸 수 없어요. 필요할 때는 '휴식하기'로 몇 분 동안 공식 앱을 열 수 있어요.
- minulo는 2026년 9월에 나와서 오래된 앱보다 평가가 적어요.

## 가이드

- [인스타그램을 DM만 쓰는 방법](https://minulo.app/ko/instagram-dms-only.html)
- [인스타그램 앱에서 릴스를 없앨 수 있을까?](https://minulo.app/ko/remove-reels-from-instagram-app.html)
- [틱톡을 메시지만 쓰는 방법](https://minulo.app/ko/tiktok-dms-only.html)
- [인스타그램을 습관적으로 여는 걸 멈추는 방법](https://minulo.app/ko/stop-opening-instagram-out-of-habit.html)
- [단톡 때문에 인스타를 못 지우는 학생에게](https://minulo.app/ko/instagram-group-chats-without-reels.html)
- [릴스를 숨기는 앱 비교](https://minulo.app/ko/alternatives.html)
- [minulo 안전한가요? 볼 수 있는 것과 없는 것](https://minulo.app/ko/is-minulo-safe.html)
- [아이폰에서 인스타 차단하는 방법](https://minulo.app/ko/block-instagram-on-iphone.html)
- [아이폰에서 틱톡 차단하는 방법](https://minulo.app/ko/block-tiktok-on-iphone.html)
- [인스타 탐색 탭 없애는 법](https://minulo.app/ko/hide-instagram-explore.html)
- [인스타 팔로잉 피드만 보는 법](https://minulo.app/ko/instagram-following-feed-only.html)
- [유튜브 쇼츠 피드 시간 제한](https://minulo.app/ko/youtube-shorts-feed-limit.html)
