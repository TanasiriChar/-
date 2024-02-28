<template>
    <div>
        <header>
        <nav>
          <h1>Tanasiri K</h1>
          <NuxtLink to="/">หน้าเเรก</NuxtLink>
          <NuxtLink to="/about">เกี่ยวกับเรา</NuxtLink>
          <NuxtLink to="/products">รายละเอียดข้อมูล</NuxtLink>
        </nav>
     </header>
    <div>
        <slot/>
    </div>
    </div>
</template>

<script setup>

</script>

<style coped>
nav{
  margin: 10px auto;
  padding: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
  background:#333;
}
nav a{
  color: white;
  text-decoration: none;
  margin-left: 12px;
  font-size: 18px;
  padding: 10px;
}
nav a:hover{
  color: orange;
}
.logo{
  margin-right: auto;
  padding-left: 10px;
  color: white;
}
</style>