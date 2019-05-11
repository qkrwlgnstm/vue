<template>
    <div class="wrap">
        <div class="container bs-docs-container">

            <div class="row">
                <div class="col-md-9" role="main">
                    <dropdown></dropdown>
                    <btn></btn>
                    <navigation></navigation>
                </div>
            
                <div class="col-md-3" role="complementary">
                    <nav class="bs-docs-sidebar hidden-print hidden-xs hidden-sm affix-top">
                        <ul class="nav bs-docs-sidenav">
                            <li class="">
                                <a href="#glyphicons">아이콘 (Glyphicons)</a>
                                <ul class="nav">
                                    <li class=""><a href="#glyphicons-glyphs">사용가능한 기호</a></li>
                                    <li class=""><a href="#glyphicons-how-to-use">사용법</a></li>
                                    <li class=""><a href="#glyphicons-examples">예제</a></li>
                                </ul>
                            </li>
                            <li>
                                <a href="#dropdowns">드롭다운</a>
                                <ul class="nav">
                                    <li><a href="#dropdowns-example">예제</a></li>
                                    <li><a href="#dropdowns-alignment">정렬</a></li>
                                    <li><a href="#dropdowns-headers">헤더</a></li>
                                    <li><a href="#dropdowns-divider">구분선</a></li>
                                    <li><a href="#dropdowns-disabled">비활성화된 메뉴 항목</a></li>
                                </ul>
                            </li>
                        </ul>
                    </nav>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
// @ is an alias to /src
import navigation from '@/components/nav.vue'
import btn from '@/components/button.vue'
import dropdown from '@/components/dropdown.vue'

export default {
  name: 'home',
  components: {
    dropdown : dropdown,
    btn : btn,
    navigation : navigation
  }
}
</script>
