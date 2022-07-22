<template>
    <header>
        <div class="container">
            <nav>
            <div class="logo"><img src="../assets/img/dc-logo.png" alt=""></div>
            <div class="links">
                <ul>
                <li v-for="link in headerLinks" 
                :key="link.text">
                    <a href="link.url">{{ link.text.toUpperCase() }}</a>
                </li>
                </ul>
            </div>
            </nav>
        </div>
    </header>

</template>

<script>
export default {
  name: 'TheHeader',
  data() {
    return {
      headerLinks: [
        {
          text: 'Characters',
          url: '#',
          current: false,
        },
        {
          text: 'Comics',
          url: '#',
          current: true,
        },
        {
          text: 'Movies',
          url: '#',
          current: false,
        },
        {
          text: 'TV',
          url: '#',
          current: false,
        },
        {
          text: 'Games',
          url: '#',
          current: false,
        },
        {
          text: 'Collectibles',
          url: '#',
          current: false,
        },
        {
          text: 'Videos',
          url: '#',
          current: false,
        },
        {
          text: 'Fans',
          url: '#',
          current: false,
        },
        {
          text: 'News',
          url: '#',
          current: false,
        },
        {
          text: 'Shop',
          url: '#',
          current: false,
        }
    ]
  }
  }
}

</script>

<style lang="scss" scoped>
header {
    flex-basis: 150px;
    flex-shrink: 1;
    background-image: linear-gradient(black 30px, white 30px);

    nav {

        padding-top: 50px;
        padding-bottom: 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;   
            .logo {
                width: 80px;
            }     
            ul {
                display: flex;
                li {
                    font-size: 0.8rem;
                    font-weight: bold;
                    margin: 10px;
                    a {
                        color: black;
                        padding: 5px;
                        &:hover {
                            color:#0C7CEC;
                        }
                        &.active {
                            border-bottom: 3px solid #0C7CEC;
                        }
                    }
                }
            }
    }
}
</style>