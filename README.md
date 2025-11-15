📌 주요 기능별 API/URL 목록

📚 도서/메인/기타
메인 페이지 & 도서 목록 조회(검색 포함)	GET	/ , /books
도서 상세 조회	GET	/books/{id}
베스트셀러 조회	GET	/bestsellers
추천 도서 조회	GET	/recommended
고객센터/FAQ	GET	/faq

👤 회원 / 인증

로그인 폼	GET	/member/loginform
로그인 처리	POST	/member/login
로그아웃	GET	/member/logout
회원가입 폼	GET	/member/registerform
회원가입 처리	POST	/member/join
내 정보 조회	GET	/member/info
내 정보 수정 폼	GET	/member/editinfo
내 정보 수정 처리	POST	/member/editinfo

🛒 장바구니

장바구니 페이지	GET	/cart
상품 추가	POST	/cart/add
수량 변경	POST	/cart/update
상품 제거	POST	/cart/remove

💳 주문 / 결제

단일 상품 바로 구매	POST	/orders/buyNow
장바구니 결제하기	POST	/orders/checkout
결제 정보 확인 페이지	GET	/orders/payment
결제 확정(주문 등록)	POST	/orders/confirm
내 주문 내역 조회	GET	/orders/member/orderlist

👑 관리자 기능 (ADMIN)

📘 도서 관리

도서 목록 & 통계	GET	/admin/books
도서 추가 폼	GET	/admin/addbook
도서 추가 처리	POST	/admin/save
도서 상세 조회	GET	/admin/books/detail?id={id}
도서 수정 폼	GET	/admin/books/edit?id={id}
도서 수정 처리	POST	/admin/books/update
도서 삭제	POST	/admin/books/delete
리뷰 삭제	POST	/admin/reviews/delete

👥 회원 관리

회원 목록 & 통계	GET	/admin/adminmemberlist
회원 수정 폼	GET	/admin/adminmemberlist/edit?userId={userId}
회원 수정 처리	POST	/admin/adminmemberlist/update
회원 삭제	POST	/admin/adminmemberlist/delete

📦 주문 관리
주문 목록 & 통계	GET	/admin/adminorderlist
주문 상세 조회	GET	/admin/adminorderlist/detail?transactionId={id}
