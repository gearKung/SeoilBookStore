localhost:8888
🔗 주요 기능별 URL 목록 
도서/메인/기타 | 메인 페이지 및 도서 목록 조회 (검색 포함) | GET | / 또는 /books

도서/메인/기타 | 도서 상세 정보 조회 | GET | /books/{id} (예: /books/123)

도서/메인/기타 | 베스트셀러 목록 조회 | GET | /bestsellers

도서/메인/기타 | 추천 도서 목록 조회 | GET | /recommended

도서/메인/기타 | 고객센터/FAQ 페이지 조회 | GET | /faq

회원/인증 | 로그인 폼 페이지 표시 | GET | /member/loginform

회원/인증 | 로그인 처리 | POST | /member/login

회원/인증 | 로그아웃 처리 | GET | /member/logout

회원/인증 | 회원가입 폼 페이지 표시 | GET | /member/registerform

회원/인증 | 회원가입 처리 | POST | /member/join

회원/인증 | 내 정보 조회 페이지 표시 | GET | /member/info

회원/인증 | 내 정보 수정 폼 페이지 표시 | GET | /member/editinfo

회원/인증 | 내 정보 수정 처리 | POST | /member/editinfo

주문/장바구니 | 장바구니 목록 페이지 조회 | GET | /cart

주문/장바구니 | 장바구니에 상품 추가 | POST | /cart/add

주문/장바구니 | 장바구니 상품 수량 변경 | POST | /cart/update

주문/장바구니 | 장바구니에서 상품 제거 | POST | /cart/remove

주문/결제 | 단일 상품 '바로 구매' 처리 (결제 전 단계) | POST | /orders/buyNow

주문/결제 | 장바구니 '결제하기' 처리 (결제 전 단계) | POST | /orders/checkout

주문/결제 | 주문/결제 정보 확인 페이지 표시 | GET | /orders/payment

주문/결제 | 최종 결제 확정 및 주문 등록 처리 | POST | /orders/confirm

주문/결제 | 내 주문 내역 조회 | GET | /orders/member/orderlist

👑 관리자 기능 (ADMIN 권한 필요)

도서 관리 목록 및 통계 조회 | GET | /admin/books

도서 추가 폼 페이지 표시 | GET | /admin/addbook

도서 추가 처리 | POST | /admin/save

도서 상세 정보 조회 (관리자용) | GET | /admin/books/detail?id={id}

도서 수정 폼 페이지 표시 | GET | /admin/books/edit?id={id}

도서 수정 처리 | POST | /admin/books/update

도서 삭제 처리 | POST | /admin/books/delete

리뷰 삭제 처리 (관리자용) | POST | /admin/reviews/delete

회원 관리 목록 및 통계 조회 | GET | /admin/adminmemberlist

회원 수정 폼 페이지 표시 | GET | /admin/adminmemberlist/edit?userId={userId}

회원 수정 처리 | POST | /admin/adminmemberlist/update

회원 삭제 처리 | POST | /admin/adminmemberlist/delete

문 관리 목록 및 통계 조회 | GET | /admin/adminorderlist

주문 상세 조회 (거래 ID 기준) | GET | /admin/adminorderlist/detail?transactionId={id}
