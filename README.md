# portalhsebde.github.io
HSE Portal PT. BERLIAN DUTA ENERGI
body {
    font-family: 'Segoe UI', Arial, sans-serif;
    margin: 0;
    background: #f4f6f8;
    color: #222;
}
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #1e293b;
    color: #fff;
    padding: 1rem 2rem;
}
.logo {
    font-size: 2rem;
    font-weight: bold;
    letter-spacing: 2px;
}
.languages {
    display: flex;
    gap: 0.5rem;
}
.flag {
    width: 32px;
    height: 20px;
    border-radius: 4px;
    box-shadow: 0 1px 4px rgba(0,0,0,0.1);
}
.user {
    font-size: 1rem;
    background: #334155;
    padding: 0.5rem 1rem;
    border-radius: 20px;
    display: flex;
    align-items: center;
    gap: 0.5rem;
}
.initial {
    background: #fbbf24;
    color: #222;
    border-radius: 50%;
    padding: 0.2rem 0.6rem;
    font-weight: bold;
}
main {
    padding: 2rem 1rem 5rem 1rem;
    max-width: 900px;
    margin: auto;
}
section {
    margin-bottom: 2rem;
}
h2 {
    margin-bottom: 1rem;
    color: #1e293b;
}
.cards {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
}
.card {
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(30,41,59,0.08);
    padding: 1.2rem 1rem;
    flex: 1 1 160px;
    min-width: 140px;
    text-align: center;
    transition: box-shadow 0.2s;
    cursor: pointer;
}
.card:hover {
    box-shadow: 0 4px 16px rgba(30,41,59,0.15);
}
.card i {
    font-size: 2rem;
    margin-bottom: 0.5rem;
    color: #2563eb;
}
.card p {
    margin: 0;
    font-size: 1.1rem;
    font-weight: 500;
}
.bottom-nav {
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
    background: #fff;
    box-shadow: 0 -2px 8px rgba(30,41,59,0.08);
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 0.7rem 0;
    z-index: 100;
}
.nav-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 1rem;
    color: #64748b;
    cursor: pointer;
    transition: color 0.2s;
}
.nav-item.active, .nav-item:hover {
    color: #2563eb;
}
.nav-item i {
    font-size: 1.5rem;
    margin-bottom: 0.2rem;
}
@media (max-width: 600px) {
    main {
        padding: 1rem 0.2rem 5rem 0.2rem;
    }
    .cards {
        flex-direction: column;
        gap: 0.7rem;
    }
    .card {
        min-width: 100%;
    }
    header {
        flex-direction: column;
        gap: 0.7rem;
        padding: 1rem 0.5rem;
    }
}
